
## cityrp.plugin.call

```lua
cityrp.plugin.call(string name, varargs ...)
```

#### Arguments

**string name** - Name of the function to call

**varargs ...** - Arguments to pass to the function

#### Description
Loops through all stored plugins and calls a function with the given name and the given arguments.

#### Information
* If there is an error with the each call it will be printed to the console
* Function call is wrapped in a `pcall`
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_plugin.lua#ln15)

#### Examples
```lua
	cityrp.plugin.call("Init", {})
```

#### Output
```lua
	-- Calls the function "Init" across all plugins
```
