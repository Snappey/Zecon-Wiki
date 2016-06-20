
## cityrp.access.hasAccess

```lua
cityrp.access.hasAccess(Player player, string access )
```

#### Arguments

**Player player** - Player to check

**string access** - Access Flag to check for

#### Returns

**bool** - returns true if the user has access to the given flag, false if not.

#### Description
Checks that the given player has access to the given access string (flag).

#### Information
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_access.lua#ln25)

#### Examples
```lua
	print( cityrp.access.hasAccess(Entity(1), "v") )
```

#### Output
```lua
	true
```
