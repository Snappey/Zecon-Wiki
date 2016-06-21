
## cityrp.access.playeraction

```lua
cityrp.access.playeraction(Player target, string access, string action)
```

#### Arguments

**Player target** - Player to target

**string access** - Access string (flag)

**string action** - Action string either `give` or `take`

#### Description
Used to activate a blacklist on the targeted player, takes effect immediately on the server using the given access string.

#### Information
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_access.lua#ln434)

#### Examples
```lua
	cityrp.access.playeraction(Entity(1), "w", "take")
```

#### Output
```lua
	-- Strips weapons from the given player
```
