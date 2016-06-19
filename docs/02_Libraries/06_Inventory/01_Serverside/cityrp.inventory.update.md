
## cityrp.inventory.update

```lua
cityrp.inventory.update(Player player, string item, number amount, bool force)
```

#### Arguments

**Player player** - Players inventory to update

**string item** - Item class name to update

**number amount** - Amount of the item to give/remove (+/-)

**bool force** -  Whether it should ignore the players inventory size

#### Returns

**bool success** - Returns true if update was successful, false if it was not.

**string error** - String to send to user if it was unsuccessful

#### Description
Used to update items in the players inventory, can be used to add or remove Items.

#### Information
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_inventory.lua#ln13)

#### Examples
```lua
	print( cityrp.inventory.update(Entity(1), "ent_testing", 1, true) )
```

#### Output
```lua
	false, "This is not a valid item!"
```
