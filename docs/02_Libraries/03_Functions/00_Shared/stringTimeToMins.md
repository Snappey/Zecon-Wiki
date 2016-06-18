
## stringTimeToMins

```lua
stringTimeToMins(string str)
```

#### Arguments

**string str** - Time string to conver to minutes

#### Returns

**string timestring** - String converted to a formatted time string

#### Description
Converts a time string with the format `100<h/d/w/m>` to minutes.

#### Information
* [Source]()https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_functions.lua#ln80

#### Examples
```lua
	print(stringTimeToMins("10h"))
```

#### Output
```lua
	"600"
```



