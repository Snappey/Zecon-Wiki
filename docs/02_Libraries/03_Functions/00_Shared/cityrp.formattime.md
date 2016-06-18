
## cityrp.formattime

```lua
cityrp.formattime(number time,bool showmins )
```

#### Arguments

**number time** - The amount of time in seconds

**bool showmins** - Whether minutes should be included in the returned string

#### Returns

**string timestring** - time formatted into days/hours/minutes

#### Description
Takes time in seconds and returns a formatted string representing days, hours and minutes

#### Information
* A string can be passed for the first argument instead of a number, it will be passed through a tonumber call before processing
* If the first argument is less than 3600 (1 hour in seconds), regardless of what the second argument is it will return the string with minutes
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_functions.lua#ln34)

#### Examples
```lua
	cityrp.formattime(3000, true)
	cityrp.formattime(15000, true)
```

#### Output
```lua
	"50 Minutes"
	"4 Hours and 10 Minutes"
```
