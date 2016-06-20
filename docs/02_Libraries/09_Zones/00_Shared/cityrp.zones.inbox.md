
## cityrp.zones.inbox

```lua
cityrp.zones.inbox(Vector pos, Vector boxmin, Vector boxmax)
```

#### Arguments

**Vector pos** - Position to check

**Vector boxmin** - Minimum corner of the box

**Vector boxmax** - Maximum corner of the box

#### Returns

**bool inside** - Whether the position passed is inside the box

#### Description
Check is the position passed is within a box created from the two vectors passed.

#### Information
* Seems similar to [Vector:WithinAABox](https://wiki.garrysmod.com/page/Vector/WithinAABox)
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_zones.lua#ln47)

#### Examples
```lua
	print( cityrp.zones.inbox(Entity(1):GetPos(), Vector(-500,-500,-500) , Vector(500,500,500) ) )

	print( cityrp.zones.inbox(Vector(-600,-500, -500), Vector(-500,-500,-500) , Vector(500,500,500) ) )
```

#### Output
```lua
	true

	false
```
