
## cityrp.access.takeaccesscommand

```lua
cityrp.access.takeaccesscommand(Player player, table arguments)
```

#### Arguments

**Player player** - Player trying alter the targets access strings

**table arguments** - Table of arguments e.g. `{"Spai", "w", "10d"} `{name, access_string, time_string}`

#### Description
This function is tied to a chat command, and is used to blacklist players with access strings.

#### Information
* Id use the other functions in the library if you want to blacklist people through the library, this is used primarily for chat commands has tonnes of checks.
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_access.lua#ln234)

#### Examples
```lua
	cityrp.access.takeaccesscommand(Entity(1), {"Spai", "w", "10d"}
```

#### Output
```lua
	-- Removes Spai's weapons for 10 days
```
