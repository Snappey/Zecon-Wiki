
## cityrp.access.takeAccess

```lua
cityrp.access.takeAccess(Player player, string access)
```

#### Arguments

**Player player** - Player to target

**string access** - Access string to remove

#### Description
Adds the given access string the player.

#### Information
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_access.lua#ln71)

#### Examples
```lua
	cityrp.access.takeAccess(Entity(1), "w")
```

#### Output
```lua
	-- Adds the 'w' flag to the player
```
