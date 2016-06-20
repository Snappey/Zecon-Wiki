
## cityrp.access.blacklistcommand

```lua
cityrp.access.blacklistcommand(Player player, table arguments)
```

#### Arguments

**Player player** - Player to blacklist

**table arguments** - Arguments e.g. `{"Spai", "President", "50m"}`

#### Description
Blacklists the given player from a job or item(?).

#### Information
* This function doesnt actually blacklist the player, instead the arguments are passed onto `cityrp.access.takecommand`
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_access.lua#ln382)

#### Examples
```lua
	cityrp.access.blaclistcommand(Entity(1), {"Spai", "President", "50m"})
```

#### Output
```lua
	-- Spai is now blacklisted from President
```
