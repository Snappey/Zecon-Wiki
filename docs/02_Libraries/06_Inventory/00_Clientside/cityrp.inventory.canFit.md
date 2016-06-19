
## cityrp.inventory.canFit

```lua
cityrp.inventory.canFit(number size)
```

#### Arguments

**number size** - Size of the item you want to insert into players inventory

#### Returns

**bool canfit** - Returns true if it can fit, false if it cannot fit.

#### Description
Checks whether an item of the size provided can fit in the local players inventory.

#### Information
* Gets the current size of the inventory and adds the size of the item, then compares it to the inventories maximum size.
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_inventory.lua#ln162)

#### Examples
```lua
	print(cityrp.inventory.canFit(200))
```

#### Output
```lua
	false
```
