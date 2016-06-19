
## cityrp.plugin.get

```lua
cityrp.plugin.get(string name)
```

#### Arguments

**string name** - Name of the plugin to get

#### Returns

**table plugin** - The Plugin with the given name

#### Description
Gets the plugin table with the given name.

#### Information
* If the plugin doesnt exist the value will be `nil`
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_plugin.lua#ln27)

#### Examples
```lua
	print(cityrp.plugin.get("stamina"))
```

#### Output
```lua
	table0xa1425
```
