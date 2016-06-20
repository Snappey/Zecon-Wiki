
## cityrp.zones.lowhigh

```lua
cityrp.zones.lowhigh(Vector vec1, Vector vec2)
```

#### Arguments

**Vector vec1** - Vector to order

**Vector vec2** - Vector to order

#### Returns

**Vector vec1** - Lowest Vector

**Vector vec2** - Highest Vector

#### Description
Reorders the vectors from low to high. Where the first vector returned is the lowest and the second vector returned is the highest.

#### Information
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_zones.lua#ln72)

#### Examples
```lua
	local vec1 = Vector(10,0,0)
	lcoal vec2 = Vector(5,0,0)

	vec1,vec2 = cityrp.zones.lowhigh(vec1,vec2)

	print(vec1, vec2)
```

#### Output
```lua
	Vector(5,0,0), Vector(10,0,0)
```
