
## cityrp.inventory.canFit

```lua
cityrp.inventory.canFit(Player player, number size)
```

#### Arguments

**Player player** - Players inventory to check

**number size** - Size of item to check

#### Returns

**bool canfit** - Returns true if it cant fit, false if it cannot fit.

#### Description
Used to check if an item of a specific size can fit inside a players inventory.

#### Information
* Serverside verion of `cityrp.inventory.canFit(number size)` allowing you to check different players inventory.
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_inventory.lua#ln77)

#### Examples
```lua
	print(cityrp.inventory.canFit(Entity(1), 5))
```

#### Output
```lua
	true
```
