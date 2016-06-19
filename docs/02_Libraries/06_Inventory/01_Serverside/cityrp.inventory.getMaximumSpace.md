
## cityrp.inventory.getMaximumSpace

```lua
cityrp.inventory.getMaximumSpace(Player player)
```

#### Arguments

**Player player** - Players inventory to check

#### Returns

**number inventorysize** - Maximum size of players inventory

#### Description
Returns the maximum size of the players inventory.

#### Information
* Functionally works the same as the clientside version.
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_inventory.lua#ln45)

#### Examples
```lua
	print(cityrp.inventory.getMaximumSpace(Entiy(1)))
```

#### Output
```lua
	50
```
