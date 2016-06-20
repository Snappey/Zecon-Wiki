
## cityrp.access.Load

```lua
cityrp.access.Load(Player player)
```

#### Arguments

**Player player** - Player to target

#### Description
Loads the targeted players blacklists from the database, and then applies them on the server.

#### Information
* Presumably ran when a player joins, as its indexed to the player object.
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_access.lua#ln106)

#### Examples
```lua
	cityrp.access.Load(Entity(1))
```

#### Output
```lua
	-- Loads blacklists for Spai
```
