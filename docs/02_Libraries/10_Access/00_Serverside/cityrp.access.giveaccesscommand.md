
## cityrp.access.giveaccesscommand

```lua
cityrp.access.giveaccesscommand(Player player, table arguments)
```

#### Arguments

**Player player** - Player to target

**Table arguments** - Table of arguments e.g. `{Target, Access}`


#### Description
Used to give access to an access string, called by a chat command.

#### Information
* Linked up to a chat command so has some pretty long checks to make sure everything works correctly, just use `cityrp.access.giveAccess`.
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_access.lua#ln121)

#### Examples
```lua
	cityrp.access.giveaccesscommand(Entity(1), {Entity(1), "v"})
```

#### Output
```lua
	-- Gives Spai access to vehicles
```
