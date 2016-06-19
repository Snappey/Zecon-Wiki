
## playerInitInventory

```lua
playerInitInventory(Player player)
```

#### Arguments

**Player player** - The players inventory to network

#### Returns

**bool success** - If the network was succesful

#### Description
Sends the players inventory to them when the `PlayerInitialized` hook is called.

#### Information
* Local function so it cannot be called
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_inventory.lua#ln87)

#### Examples
```lua
	playerInitInventory(Entity(1))
```

#### Output
```lua
	-- Players Inventory is networked
```
