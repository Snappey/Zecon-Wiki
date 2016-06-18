
## comma_value

```lua
comma_value(string amount)
```

#### Arguments

**string amount** - The string to add commas too.

#### Returns

**string formattedamount** - The formatted string with commas added

#### Description
Adds commas between each group of 3 digits.

#### Information
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_functions.lua#ln141)

#### Examples
```lua
	print(comma_value("123456789"))
```

#### Output
```lua
	"123,456,789"
```



