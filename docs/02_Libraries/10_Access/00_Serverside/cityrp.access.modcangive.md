
## cityrp.access.modcangive

```lua
cityrp.access.modcangive(Player admin, Player target, string access)
```

#### Arguments

**Player admin** - The player trying to give access

**Player target** - The player being given access

**string access** - Access string being given to the target

#### Returns

**bool** - Whether the admin is able to give access

#### Description
Used internally by `cityrp.access.giveaccesscommand` checks if the passed `admin` is the player who took the access away.

#### Information
* Only used once by `cityrp.access.giveaccesscommand` to make sure that moderators can only give permissions to people they took permissions away from.
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_access.lua#ln222)