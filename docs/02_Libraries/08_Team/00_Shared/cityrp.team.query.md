
## cityrp.team.query

```lua
cityrp.team.query(<string/number> name, string key, vararg default)
```

#### Arguments

**<string/number> name** - Name or index of the team to query

**string key** - Key of the team table to get

**vararg default** - If the key is equal to nil return this value

#### Returns

**vararg keyvalue** - The value stored at `teamtable[key]` or the default value if it was unsuccessful

#### Description
Used to query a jobs table for a certain value

#### Information
* Call `cityrp.team.get` to get the correct job table
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_team.lua#ln78)

#### Examples
```lua
	print(cityrp.team.query("President", "salary", -10))
	print(cityrp.team.query("President", "celery", -100))
```

#### Output
```lua
	 500
	-100
```
