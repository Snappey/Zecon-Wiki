
## cityrp.inventory.getSize

```lua
cityrp.inventory.getSize(Player player)
```

#### Arguments

**Player player** - Players inventory to check

#### Returns

**number size** - Size of players inventory

#### Description
Returns the size of the players inventory **not** including their items.

#### Information
* Functionally the same as the clientside version
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_inventory.lua#ln62)

#### Examples
```lua
	print(cityrp.inventory.getSize(Entity(1)))
```

#### Output
```lua
	15
```
