
## cityrp.access.unblacklistcommand

```lua
cityrp.access.unblacklistcommand(Player player, table arguments)
```

#### Arguments

**Player player** - Player trying to unblacklist with the given arguments

**table arguments** - Table of arguments e.g. `{Target, Access}` or `{"Spai", "w"}`

#### Description
Links to the unblacklist chat command, unblacklists the user with the given arguments.

#### Information
* Id use the other functions in the library if you want to blacklist people through the library, this is used primarily for chat commands has tonnes of checks.


#### Examples
```lua
	cityrp.access.unblacklistcommand(Entity(1), {"Spai", "w"})
```

#### Output
```lua
	-- Removes Spais blackist with the flag 'w'
```
