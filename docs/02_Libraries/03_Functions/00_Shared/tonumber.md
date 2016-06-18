
## tonumber

```lua
tonumber(vararg str, number base)
```

#### Arguments

**vararg str** - Value to convert to a number

**number base** - Base system used for the converting number e.g. (10 is base 10)

#### Returns

**number convertedval** - Value converted to a number, if it fails the value is nil.

#### Description
Overrides the orginial tonumber within lua, this version checks if the provided value is a string equal to "NaN" or "inf" if so prevents the conversion.

#### Information
* This protects from exploits I believe, can fuck with some money systems using "NaN" etc.. Will need checking though as Im not 100% sure.
* Original function is called after the check has been done
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_functions.lua#ln161)

#### Examples
```lua
	print(tonumber("134"))
	print(tonumber("NaN"))
```

#### Output
```lua
	134
	nil
```
