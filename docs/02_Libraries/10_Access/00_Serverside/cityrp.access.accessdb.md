
## cityrp.access.accessdb

```lua
cityrp.access.accessdb(string aname, string asteamid, string tname, string tsteamid, string access, string action, string timeuntill, string reason)
```

#### Arguments

**string aname** - Admins name

**string asteamid** - Admins steamid

**string tname** - Targets name

**string tsteamid** - Targets steamid

**string access** - Access string e.g. `p`

**string action** - Either `take` or `give`

**string timeuntill** - Time it should expire e.g. `10h` or `10m` used [stringTimeToMins](Functions/Shared/stringTimeToMins) 

**string reason** - Reason for taking/giving access

#### Description
Used to insert logs into the database about (un)blacklists.

#### Information
* `give` will only work if it was previously taken away
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_access.lua#ln424)

#### Examples

[Example](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_access.lua#ln313)