
## cityrp.zones.vectotable

```lua
cityrp.zones.vectotable(Vector vec)
```

#### Arguments

**Vector vec** - Vector to conver to a table

#### Returns

**Table** - Vector converted to a table

#### Description
Converts the given vector to a table.

#### Information
* Not sure what the point of this is as you can index a vector like a table anyways. Unless Im completly misunderstanding the point of the function
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_zones.lua#ln61)

#### Examples
```lua
	PrintTable( cityrp.zones.vectotable( Vector(10,0,10) ) )
```

#### Output
```lua
	1 = 10
	2 = 0
	3 = 10
```
