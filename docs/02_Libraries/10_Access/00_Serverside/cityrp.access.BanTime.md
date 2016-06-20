
## cityrp.access.BantTime

```lua
cityrp.access.BanTime(Player player, string access)
```

#### Arguments

**Player player** - Players to check

**string access** - Access string to check

#### Returns

**string** - Time until access is given back

#### Description
Checks the players ban length for the given access string.

#### Information
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_access.lua#ln82)

#### Examples
```lua
	print( cityrp.access.BanTime(Entity(1), "p"))
```

#### Output
```lua
	"50 Minutes"
```
