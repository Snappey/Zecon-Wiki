
## cityrp.entity.detonate
```lua
cityrp.entity.detonate(Entity ent,number range)
```

#### Arguments

**Entity ent** - Entity to check 

**number range** - Radius of the check

#### Description
Used in the `ent_breach` entity, checks for all owned props in the given radius of the entity passed then removes them.

#### Information
* Only called in the `ent_breach` entity
* Declared as a shared library but only has a serverside function?
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_entity.lua#ln11)

#### Examples
```lua
	cityrp.entity.detonate(breach, 64);
```

#### Output
```lua
	All props within a 64 unit radius of the entity passed are removed
```



