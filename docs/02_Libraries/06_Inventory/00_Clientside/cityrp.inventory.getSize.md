
## cityrp.inventory.getSize

```lua
cityrp.inventory.getSize()
```

#### Returns

**number size** - Gets the size of the local players inventory

#### Description
Returns the size of the local players inventory **not** including their items.

#### Information
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_inventory.lua#ln145)

#### Examples
```lua
	print(cityrp.inventory.getSize() .. "/" .. cityrp.inventory.getMaximumSpace())
```

#### Output
```lua
	15/50
```
