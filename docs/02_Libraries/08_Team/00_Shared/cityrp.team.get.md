
## cityrp.team.get
```lua
cityrp.team.get(<string/number> name)
```

#### Arguments

**<string/number> name** Gets the corresponding team, can either be the index or the name.

#### Returns

**table teamdata** - Returns a table with data about the team e.g. (Model, description, salary)

#### Description
Gets the team table by using either the team index or the team name.

#### Information
* Using the team index is much faster than using the team name.
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_team.lua#ln51)

#### Examples
```lua
	print( cityrp.team.get("President") )
```

#### Output
```lua
	table 0x0a52c3
```
