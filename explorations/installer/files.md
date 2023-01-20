# Files

```
.
├── assets
│   ├── babel.config.json
│   ├── js
│   │   └── phoenix
│   │       ├── ajax.js
│   │       ├── channel.js
│   │       ├── constants.js
│   │       ├── index.js
│   │       ├── longpoll.js
│   │       ├── presence.js
│   │       ├── push.js
│   │       ├── serializer.js
│   │       ├── socket.js
│   │       ├── timer.js
│   │       └── utils.js
│   ├── package-lock.json
│   ├── package.json
│   └── test
│       ├── channel_test.js
│       ├── presence_test.js
│       ├── serializer.js
│       ├── serializer_test.js
│       └── socket_test.js
├── config
│   └── config.exs
├── installer
│   ├── README.md
│   ├── lib
│   │   ├── mix
│   │   │   └── tasks
│   │   │       ├── local.phx.ex
│   │   │       ├── phx.new.ecto.ex
│   │   │       ├── phx.new.ex
│   │   │       └── phx.new.web.ex
│   │   └── phx_new
│   │       ├── ecto.ex
│   │       ├── generator.ex
│   │       ├── mailer.ex
│   │       ├── project.ex
│   │       ├── single.ex
│   │       ├── umbrella.ex
│   │       └── web.ex
│   ├── mix.exs
│   ├── mix.lock
│   ├── templates
│   │   ├── phx_assets
│   │   │   ├── app.css
│   │   │   └── app.js
│   │   ├── phx_ecto
│   │   │   ├── data_case.ex
│   │   │   ├── formatter.exs
│   │   │   ├── repo.ex
│   │   │   └── seeds.exs
│   │   ├── phx_gettext
│   │   │   ├── en
│   │   │   │   └── LC_MESSAGES
│   │   │   │       └── errors.po
│   │   │   ├── errors.pot
│   │   │   └── gettext.ex
│   │   ├── phx_live
│   │   │   └── assets
│   │   │       └── topbar.js
│   │   ├── phx_mailer
│   │   │   └── lib
│   │   │       └── app_name
│   │   │           └── mailer.ex
│   │   ├── phx_single
│   │   │   ├── README.md
│   │   │   ├── config
│   │   │   │   ├── config.exs
│   │   │   │   ├── dev.exs
│   │   │   │   ├── prod.exs
│   │   │   │   ├── runtime.exs
│   │   │   │   └── test.exs
│   │   │   ├── formatter.exs
│   │   │   ├── gitignore
│   │   │   ├── lib
│   │   │   │   ├── app_name
│   │   │   │   │   └── application.ex
│   │   │   │   ├── app_name.ex
│   │   │   │   └── app_name_web.ex
│   │   │   ├── mix.exs
│   │   │   └── test
│   │   │       └── test_helper.exs
│   │   ├── phx_static
│   │   │   ├── app.css
│   │   │   ├── app.js
│   │   │   ├── favicon.ico
│   │   │   ├── phoenix.css
│   │   │   ├── phoenix.png
│   │   │   └── robots.txt
│   │   ├── phx_test
│   │   │   ├── controllers
│   │   │   │   └── page_controller_test.exs
│   │   │   ├── live
│   │   │   │   └── page_live_test.exs
│   │   │   ├── support
│   │   │   │   └── conn_case.ex
│   │   │   └── views
│   │   │       ├── error_view_test.exs
│   │   │       ├── layout_view_test.exs
│   │   │       └── page_view_test.exs
│   │   ├── phx_umbrella
│   │   │   ├── README.md
│   │   │   ├── apps
│   │   │   │   ├── app_name
│   │   │   │   │   ├── README.md
│   │   │   │   │   ├── config
│   │   │   │   │   │   └── config.exs
│   │   │   │   │   ├── formatter.exs
│   │   │   │   │   ├── gitignore
│   │   │   │   │   ├── lib
│   │   │   │   │   │   ├── app_name
│   │   │   │   │   │   │   └── application.ex
│   │   │   │   │   │   └── app_name.ex
│   │   │   │   │   ├── mix.exs
│   │   │   │   │   └── test
│   │   │   │   │       └── test_helper.exs
│   │   │   │   └── app_name_web
│   │   │   │       ├── README.md
│   │   │   │       ├── config
│   │   │   │       │   ├── config.exs
│   │   │   │       │   ├── dev.exs
│   │   │   │       │   ├── prod.exs
│   │   │   │       │   ├── runtime.exs
│   │   │   │       │   └── test.exs
│   │   │   │       ├── formatter.exs
│   │   │   │       ├── gitignore
│   │   │   │       ├── lib
│   │   │   │       │   ├── app_name
│   │   │   │       │   │   └── application.ex
│   │   │   │       │   └── app_name.ex
│   │   │   │       ├── mix.exs
│   │   │   │       └── test
│   │   │   │           └── test_helper.exs
│   │   │   ├── config
│   │   │   │   ├── config.exs
│   │   │   │   ├── dev.exs
│   │   │   │   ├── extra_config.exs
│   │   │   │   ├── prod.exs
│   │   │   │   ├── runtime.exs
│   │   │   │   └── test.exs
│   │   │   ├── formatter.exs
│   │   │   ├── gitignore
│   │   │   └── mix.exs
│   │   └── phx_web
│   │       ├── controllers
│   │       │   └── page_controller.ex
│   │       ├── endpoint.ex
│   │       ├── router.ex
│   │       ├── telemetry.ex
│   │       ├── templates
│   │       │   ├── layout
│   │       │   │   ├── app.html.heex
│   │       │   │   ├── live.html.heex
│   │       │   │   └── root.html.heex
│   │       │   └── page
│   │       │       └── index.html.heex
│   │       └── views
│   │           ├── error_helpers.ex
│   │           ├── error_view.ex
│   │           ├── layout_view.ex
│   │           └── page_view.ex
│   └── test
│       ├── mix_helper.exs
│       ├── phx_new_ecto_test.exs
│       ├── phx_new_test.exs
│       ├── phx_new_umbrella_test.exs
│       ├── phx_new_web_test.exs
│       └── test_helper.exs
├── integration_test
│   ├── README.md
│   ├── config
│   │   └── config.exs
│   ├── docker-compose.yml
│   ├── mix.exs
│   ├── mix.lock
│   └── test
│       ├── code_generation
│       │   ├── app_with_defaults_test.exs
│       │   ├── app_with_mssql_adapter_test.exs
│       │   ├── app_with_mysql_adapter_test.exs
│       │   ├── app_with_no_options_test.exs
│       │   ├── app_with_sqlite3_adapter.exs
│       │   └── umbrella_app_with_defaults_test.exs
│       ├── support
│       │   └── code_generator_case.ex
│       └── test_helper.exs
├── lib
│   ├── mix
│   │   ├── phoenix
│   │   │   ├── context.ex
│   │   │   └── schema.ex
│   │   ├── phoenix.ex
│   │   └── tasks
│   │       ├── compile.phoenix.ex
│   │       ├── phx.digest.clean.ex
│   │       ├── phx.digest.ex
│   │       ├── phx.ex
│   │       ├── phx.gen.auth
│   │       │   ├── hashing_library.ex
│   │       │   ├── injector.ex
│   │       │   └── migration.ex
│   │       ├── phx.gen.auth.ex
│   │       ├── phx.gen.cert.ex
│   │       ├── phx.gen.channel.ex
│   │       ├── phx.gen.context.ex
│   │       ├── phx.gen.embedded.ex
│   │       ├── phx.gen.ex
│   │       ├── phx.gen.html.ex
│   │       ├── phx.gen.json.ex
│   │       ├── phx.gen.live.ex
│   │       ├── phx.gen.notifier.ex
│   │       ├── phx.gen.presence.ex
│   │       ├── phx.gen.release.ex
│   │       ├── phx.gen.schema.ex
│   │       ├── phx.gen.secret.ex
│   │       ├── phx.gen.socket.ex
│   │       ├── phx.routes.ex
│   │       └── phx.server.ex
│   ├── phoenix
│   │   ├── channel
│   │   │   └── server.ex
│   │   ├── channel.ex
│   │   ├── code_reloader
│   │   │   ├── proxy.ex
│   │   │   └── server.ex
│   │   ├── code_reloader.ex
│   │   ├── config.ex
│   │   ├── controller
│   │   │   └── pipeline.ex
│   │   ├── controller.ex
│   │   ├── digester
│   │   │   ├── compressor.ex
│   │   │   └── gzip.ex
│   │   ├── digester.ex
│   │   ├── endpoint
│   │   │   ├── cowboy2_adapter.ex
│   │   │   ├── cowboy2_handler.ex
│   │   │   ├── render_errors.ex
│   │   │   ├── supervisor.ex
│   │   │   └── watcher.ex
│   │   ├── endpoint.ex
│   │   ├── exceptions.ex
│   │   ├── logger.ex
│   │   ├── naming.ex
│   │   ├── param.ex
│   │   ├── presence.ex
│   │   ├── router
│   │   │   ├── console_formatter.ex
│   │   │   ├── helpers.ex
│   │   │   ├── resource.ex
│   │   │   ├── route.ex
│   │   │   └── scope.ex
│   │   ├── router.ex
│   │   ├── socket
│   │   │   ├── message.ex
│   │   │   ├── pool_supervisor.ex
│   │   │   ├── serializer.ex
│   │   │   ├── serializers
│   │   │   │   ├── v1_json_serializer.ex
│   │   │   │   └── v2_json_serializer.ex
│   │   │   └── transport.ex
│   │   ├── socket.ex
│   │   ├── test
│   │   │   ├── channel_test.ex
│   │   │   └── conn_test.ex
│   │   ├── token.ex
│   │   └── transports
│   │       ├── long_poll.ex
│   │       ├── long_poll_server.ex
│   │       └── websocket.ex
│   └── phoenix.ex
├── logo.png
├── mix.exs
├── mix.lock
├── package.json
├── priv
│   ├── static
│   │   ├── favicon.ico
│   │   ├── phoenix.cjs.js
│   │   ├── phoenix.cjs.js.map
│   │   ├── phoenix.js
│   │   ├── phoenix.min.js
│   │   ├── phoenix.mjs
│   │   ├── phoenix.mjs.map
│   │   └── phoenix.png
│   └── templates
│       ├── phx.gen.auth
│       │   ├── _menu.html.heex
│       │   ├── auth.ex
│       │   ├── auth_test.exs
│       │   ├── confirmation_controller.ex
│       │   ├── confirmation_controller_test.exs
│       │   ├── confirmation_edit.html.heex
│       │   ├── confirmation_new.html.heex
│       │   ├── confirmation_view.ex
│       │   ├── conn_case.exs
│       │   ├── context_fixtures_functions.ex
│       │   ├── context_functions.ex
│       │   ├── migration.ex
│       │   ├── notifier.ex
│       │   ├── registration_controller.ex
│       │   ├── registration_controller_test.exs
│       │   ├── registration_new.html.heex
│       │   ├── registration_view.ex
│       │   ├── reset_password_controller.ex
│       │   ├── reset_password_controller_test.exs
│       │   ├── reset_password_edit.html.heex
│       │   ├── reset_password_new.html.heex
│       │   ├── reset_password_view.ex
│       │   ├── routes.ex
│       │   ├── schema.ex
│       │   ├── schema_token.ex
│       │   ├── session_controller.ex
│       │   ├── session_controller_test.exs
│       │   ├── session_new.html.heex
│       │   ├── session_view.ex
│       │   ├── settings_controller.ex
│       │   ├── settings_controller_test.exs
│       │   ├── settings_edit.html.heex
│       │   ├── settings_view.ex
│       │   └── test_cases.exs
│       ├── phx.gen.channel
│       │   ├── channel.ex
│       │   ├── channel_case.ex
│       │   └── channel_test.exs
│       ├── phx.gen.context
│       │   ├── access_no_schema.ex
│       │   ├── context.ex
│       │   ├── context_test.exs
│       │   ├── fixtures.ex
│       │   ├── fixtures_module.ex
│       │   ├── schema_access.ex
│       │   └── test_cases.exs
│       ├── phx.gen.embedded
│       │   └── embedded_schema.ex
│       ├── phx.gen.html
│       │   ├── controller.ex
│       │   ├── controller_test.exs
│       │   ├── edit.html.heex
│       │   ├── form.html.heex
│       │   ├── index.html.heex
│       │   ├── new.html.heex
│       │   ├── show.html.heex
│       │   └── view.ex
│       ├── phx.gen.json
│       │   ├── changeset_view.ex
│       │   ├── controller.ex
│       │   ├── controller_test.exs
│       │   ├── fallback_controller.ex
│       │   └── view.ex
│       ├── phx.gen.live
│       │   ├── form_component.ex
│       │   ├── form_component.html.heex
│       │   ├── index.ex
│       │   ├── index.html.heex
│       │   ├── live_helpers.ex
│       │   ├── live_test.exs
│       │   ├── show.ex
│       │   └── show.html.heex
│       ├── phx.gen.notifier
│       │   ├── notifier.ex
│       │   └── notifier_test.exs
│       ├── phx.gen.presence
│       │   └── presence.ex
│       ├── phx.gen.release
│       │   ├── Dockerfile.eex
│       │   ├── dockerignore.eex
│       │   ├── rel
│       │   │   ├── migrate.bat.eex
│       │   │   ├── migrate.sh.eex
│       │   │   ├── server.bat.eex
│       │   │   └── server.sh.eex
│       │   └── release.ex
│       ├── phx.gen.schema
│       │   ├── migration.exs
│       │   └── schema.ex
│       └── phx.gen.socket
│           ├── socket.ex
│           └── socket.js
└── test
    ├── fixtures
    │   ├── digest
    │   │   ├── cleaner
    │   │   │   ├── cache_manifest.json
    │   │   │   └── latest_not_most_recent_cache_manifest.json
    │   │   ├── compile
    │   │   │   ├── cache_manifest.json
    │   │   │   └── cache_manifest_upgrade.json
    │   │   └── priv
    │   │       ├── output
    │   │       │   ├── foo-288ea8c7954498e65663c817382eeac4.css
    │   │       │   └── foo-d978852bea6530fcd197b5445ed008fd.css
    │   │       └── static
    │   │           ├── app.js
    │   │           ├── app.js.map
    │   │           ├── css
    │   │           │   └── app.css
    │   │           ├── foo.css
    │   │           ├── images
    │   │           │   └── relative.png
    │   │           ├── manifest.json
    │   │           ├── phoenix.png
    │   │           ├── precompressed.js.br
    │   │           └── precompressed.js.gz
    │   ├── hello.txt
    │   ├── ssl
    │   │   ├── cert.pem
    │   │   └── key.pem
    │   ├── templates
    │   │   ├── custom.foo
    │   │   ├── layout
    │   │   │   └── app.html.eex
    │   │   ├── no_trim.text.eex
    │   │   ├── path.html.eex
    │   │   ├── safe.html.eex
    │   │   ├── show.html.eex
    │   │   ├── trim.html.eex
    │   │   └── user
    │   │       ├── index.html.eex
    │   │       ├── profiles
    │   │       │   └── admin.html.eex
    │   │       ├── render_template.html.eex
    │   │       └── show.json.exs
    │   └── views.exs
    ├── mix
    │   ├── phoenix_test.exs
    │   └── tasks
    │       ├── phx.digest.clean_test.exs
    │       ├── phx.digest_test.exs
    │       ├── phx.gen.auth
    │       │   └── injector_test.exs
    │       ├── phx.gen.auth_test.exs
    │       ├── phx.gen.cert_test.exs
    │       ├── phx.gen.channel_test.exs
    │       ├── phx.gen.context_test.exs
    │       ├── phx.gen.embedded_test.exs
    │       ├── phx.gen.html_test.exs
    │       ├── phx.gen.json_test.exs
    │       ├── phx.gen.live_test.exs
    │       ├── phx.gen.notifier_test.exs
    │       ├── phx.gen.presence_test.exs
    │       ├── phx.gen.release_test.exs
    │       ├── phx.gen.schema_test.exs
    │       ├── phx.gen.secret_test.exs
    │       ├── phx.gen.socket_test.exs
    │       ├── phx.routes_test.exs
    │       └── phx_test.exs
    ├── phoenix
    │   ├── channel_test.exs
    │   ├── code_reloader_test.exs
    │   ├── config_test.exs
    │   ├── controller
    │   │   ├── controller_test.exs
    │   │   ├── flash_test.exs
    │   │   ├── pipeline_test.exs
    │   │   └── render_test.exs
    │   ├── digester
    │   │   └── gzip_test.exs
    │   ├── digester_test.exs
    │   ├── endpoint
    │   │   ├── endpoint_test.exs
    │   │   ├── render_errors_test.exs
    │   │   ├── supervisor_test.exs
    │   │   └── watcher_test.exs
    │   ├── integration
    │   │   ├── endpoint_test.exs
    │   │   ├── long_poll_channels_test.exs
    │   │   ├── long_poll_socket_test.exs
    │   │   ├── websocket_channels_test.exs
    │   │   └── websocket_socket_test.exs
    │   ├── logger_test.exs
    │   ├── naming_test.exs
    │   ├── param_test.exs
    │   ├── presence_test.exs
    │   ├── router
    │   │   ├── console_formatter_test.exs
    │   │   ├── forward_test.exs
    │   │   ├── helpers_test.exs
    │   │   ├── pipeline_test.exs
    │   │   ├── resource_test.exs
    │   │   ├── resources_test.exs
    │   │   ├── route_test.exs
    │   │   ├── routing_test.exs
    │   │   └── scope_test.exs
    │   ├── socket
    │   │   ├── socket_test.exs
    │   │   ├── transport_test.exs
    │   │   ├── v1_json_serializer_test.exs
    │   │   └── v2_json_serializer_test.exs
    │   ├── test
    │   │   ├── channel_test.exs
    │   │   └── conn_test.exs
    │   └── token_test.exs
    ├── support
    │   ├── endpoint_helper.exs
    │   ├── http_client.exs
    │   ├── router_helper.exs
    │   └── websocket_client.exs
    └── test_helper.exs

126 directories, 426 files
```

## Packages or Apps

- Installer
  
```
├── installer
│   ├── lib
│   │   ├── mix
│   │   │   └── tasks
│   │   │       ├── local.phx.ex
│   │   │       ├── phx.new.ecto.ex
│   │   │       ├── phx.new.ex
│   │   │       └── phx.new.web.ex
│   │   └── phx_new
│   │       ├── ecto.ex
│   │       ├── generator.ex
│   │       ├── mailer.ex
│   │       ├── project.ex
│   │       ├── single.ex
│   │       ├── umbrella.ex
│   │       └── web.ex
│   ├── mix.exs
```

- Phoenix (lib)

### Installer

```
mix phx.new hello
```

```
* creating hello/config/config.exs
* creating hello/config/dev.exs
* creating hello/config/prod.exs
* creating hello/config/runtime.exs
* creating hello/config/test.exs
* creating hello/lib/hello/application.ex
* creating hello/lib/hello.ex
* creating hello/lib/hello_web/views/error_helpers.ex
* creating hello/lib/hello_web/views/error_view.ex
* creating hello/lib/hello_web/endpoint.ex
* creating hello/lib/hello_web/router.ex
* creating hello/lib/hello_web/telemetry.ex
* creating hello/lib/hello_web.ex
* creating hello/mix.exs
* creating hello/README.md
* creating hello/.formatter.exs
* creating hello/.gitignore
* creating hello/test/support/conn_case.ex
* creating hello/test/test_helper.exs
* creating hello/test/hello_web/views/error_view_test.exs
* creating hello/lib/hello/repo.ex
* creating hello/priv/repo/migrations/.formatter.exs
* creating hello/priv/repo/seeds.exs
* creating hello/test/support/data_case.ex
* creating hello/lib/hello_web/controllers/page_controller.ex
* creating hello/lib/hello_web/views/page_view.ex
* creating hello/test/hello_web/controllers/page_controller_test.exs
* creating hello/test/hello_web/views/page_view_test.exs
* creating hello/assets/vendor/topbar.js
* creating hello/lib/hello_web/templates/layout/root.html.heex
* creating hello/lib/hello_web/templates/layout/app.html.heex
* creating hello/lib/hello_web/templates/layout/live.html.heex
* creating hello/lib/hello_web/views/layout_view.ex
* creating hello/lib/hello_web/templates/page/index.html.heex
* creating hello/test/hello_web/views/layout_view_test.exs
* creating hello/lib/hello/mailer.ex
* creating hello/lib/hello_web/gettext.ex
* creating hello/priv/gettext/en/LC_MESSAGES/errors.po
* creating hello/priv/gettext/errors.pot
* creating hello/assets/css/phoenix.css
* creating hello/assets/css/app.css
* creating hello/assets/js/app.js
* creating hello/priv/static/robots.txt
* creating hello/priv/static/images/phoenix.png
* creating hello/priv/static/favicon.ico

Fetch and install dependencies? [Yn] * running mix deps.get
```

mix/tasks/phx.new.ex

```elixir
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

lib/phx_new/single.ex

```
defmodule Phx.New.Single do
  @moduledoc false
  use Phx.New.Generator
  alias Phx.New.{Project}
```

lib/phx_new/generator.ex

```
defmodule Phx.New.Generator do
  @moduledoc false
  import Mix.Generator
  alias Phx.New.{Project}
```

Project is the struct:

```
defstruct base_path: nil,
  app: nil,
  app_mod: nil,
  app_path: nil,
  lib_web_name: nil,
  root_app: nil,
  root_mod: nil,
  project_path: nil,
  web_app: nil,
  web_namespace: nil,
  web_path: nil,
  opts: :unset,
  in_umbrella?: false,
  binding: [],
  generators: []
```

## Tests

```
$ tree test/
test/
├── mix_helper.exs
├── phx_new_ecto_test.exs
├── phx_new_test.exs
├── phx_new_umbrella_test.exs
├── phx_new_web_test.exs
└── test_helper.exs

0 directories, 6 files
```

What is this? In `mix_helper`

```
# Get Mix output sent to the current
# process to avoid polluting tests.
Mix.shell(Mix.Shell.Process)
```

```
$ mix deps.get
Resolving Hex dependencies...
Dependency resolution completed:
Unchanged:
  earmark_parser 1.4.12
  ex_doc 0.24.1
  makeup 1.0.5
  makeup_elixir 0.15.1
  makeup_erlang 0.1.1
  nimble_parsec 1.1.0
* Getting ex_doc (Hex package)
* Getting earmark_parser (Hex package)
* Getting makeup_elixir (Hex package)
* Getting makeup_erlang (Hex package)
* Getting makeup (Hex package)
* Getting nimble_parsec (Hex package)
```

```
mix test
```

