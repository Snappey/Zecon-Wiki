
## cityrp.plugin.register

```lua
cityrp.plugin.register(table plugin)
```

#### Arguments

**table plugin** - Plugin table to register

#### Description
Registers a new plugin in the `cityrp.plugin.stored` table using the `name` value from the passed table.

#### Information
* Check here for [Plugin]() Example.
* Called at the bottom of all plugins to register them in the cityrp gamemode
* Name / Author / Functions and other information are stored in the Plugin table
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_plugin.lua#ln10)

#### Examples
```lua
	cityrp.plugin.register({
		["name"] = "Stamina"
		["author"] = "Kudomiku"
		["IsRunning"] = function0x03523
		["StopRunning"] = function0x05346
		["Players"] = table0x06474
	})
```
*That will not work btw, purely an example in what a plugin table __could__ feature*
*In order to register a function a name key is required*
