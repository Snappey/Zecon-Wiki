
## cityrp.help.get

```lua
cityrp.help.get(string command)
```

#### Arguments

**string command** - The command to look up

#### Returns

**string text** - The help message associated with the command passed, or false if no command is found

#### Description
Used to find the help message with the associating command.

#### Information
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_help.lua#ln65)

#### Examples
```lua
	print(cityrp.help.get("getinfo"))
```

#### Output
```lua
	"<name|steamid|ip>"
```
