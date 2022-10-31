# Exploring OptionParser

## Exploration

[Documentation](https://hexdocs.pm/elixir/1.12/OptionParser.html)

```
argv() :: [String.t()]
options() :: [switches: keyword(), strict: keyword(), aliases: keyword()]
parsed() :: keyword() # {switch_name: atom, value: any} 
errors :: [{String.t(), String.t() | nil}]

OptionParser.parse(argv(), options()) :: {parsed(), argv(), errors()}
```

switches in the installer:

```
  @switches [dev: :boolean, assets: :boolean, ecto: :boolean,
             app: :string, module: :string, web_module: :string,
             database: :string, binary_id: :boolean, html: :boolean,
             gettext: :boolean, umbrella: :boolean, verbose: :boolean,
             live: :boolean, dashboard: :boolean, install: :boolean,
             prefix: :string, mailer: :boolean]
```

calling the parser:

```
  defp parse_opts(argv) do
    case OptionParser.parse(argv, strict: @switches) do
      {opts, argv, []} ->
        {opts, argv}
      {_opts, _argv, [switch | _]} ->
        Mix.raise "Invalid option: " <> switch_to_string(switch)
    end
  end
```

the entry point

```
  def run(argv) do
    elixir_version_check!()
    case parse_opts(argv) do
      {_opts, []} ->
        Mix.Tasks.Help.run(["phx.new"])

      {opts, [base_path | _]} ->
        generator = if opts[:umbrella], do: Umbrella, else: Single
        generate(base_path, generator, :project_path, opts)
    end
  end
```

the base path is the first argument that is not a switch

finally:

```
  defp generate(base_path, generator, path, opts) do
    base_path
    |> Project.new(opts)
    |> generator.prepare_project()
    |> Generator.put_binding()
    |> validate_project(path)
    |> generator.generate()
    |> prompt_to_install_deps(generator, path)
  end
```

The function to have a look is `Generator.put_binding`

