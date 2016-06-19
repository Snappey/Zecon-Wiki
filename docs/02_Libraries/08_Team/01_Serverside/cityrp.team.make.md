
## cityrp.team.make

```lua
cityrp.team.make(Player player, <string/number> name)
```

#### Arguments

**Player player** - Player to set job

**<string/number> name** - Name or index of the job

#### Returns

**bool success** - Returns true if it was successful, false it it was unsuccessful.

#### Description
Used to set a players job to a different job.

#### Information
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_team.lua#ln92)

#### Examples
```lua
	cityrp.team.make(Entity(1), 1)
```

#### Output
```lua
	-- Sets Spai to the first job created with the index of 1
```
