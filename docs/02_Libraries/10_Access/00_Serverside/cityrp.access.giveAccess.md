
## cityrp.access.giveAccess

```lua
cityrp.access.giveAccess(Player player, string access)
```

#### Arguments

**Player player** - Player to target

**string access** - Access string to give

#### Description
Gives the player permissions with the access string (flag).

#### Information
* Used to give players access to actions relating to the given flag
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_access.lua#ln60)

#### Examples
```lua
	cityrp.access.giveAccess(Entity(1), "v")
```

#### Output
```lua
	-- Gives Spai access to Vehicles (I think 'v' is the right flag)
```
