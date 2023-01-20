# Exploring Meta-programming

## quote and unquote

```
{atom(), keyword_list(), []}
{functionName, metadata, argumentList}
```

variable: 

```
{atom(), keyword_list(), atom()}
```

> In general, the tuples above are structured according to the following format:
>   {atom | tuple, list, list | atom}
> 1. The first element is an atom or another tuple in the same representation;
> 2. The second element is a keyword list containing metadata, like numbers and contexts;
> 3. The third element is either a list of arguments for the function call or an atom. 
>    When this element is an atom, it means the tuple represents a variable.


> there are five Elixir literals that, when quoted, return themselves (and not a tuple). They are:
>
>   :sum         #=> Atoms
>   1.0          #=> Numbers
>   [1, 2]       #=> Lists
>   "strings"    #=> Strings
>   {key, value} #=> Tuples with two elements

functions:
- quote
- unquote
- Macro.escape
- `Macro.expand_once\2` - receives a quoted expression and expands it according to the current environment.
- Macro.var/2 - create new variables inside a macro

`__ENV__` is a `%Macro.Env{}` struct
