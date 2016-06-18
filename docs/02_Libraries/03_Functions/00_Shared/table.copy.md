
## table.copy

```lua
table.copy(table orig)
```

#### Arguments

**table orig** - Table to be copied

#### Returns

**table copy** -- Copied Table

#### Description
Copies the contents of the given table to a new table, then returns the new table.

#### Information
* not sure what is wrong with table.Copy for this, but whatever. Unless Im misunderstanding this completly 
* Is also defined in cl_chatbox.lua
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_functions.lua#ln126)

#### Examples
```lua
	local tbl = {"123", "456", "789"}

	copiedwrongtbl = tbl
	copiedrighttbl = table.copy(atbl)
	copiedwrongtbl[2] = "666"

	PrintTable(tbl)
	PrintTable(copiedwrongtbl)
	Printtable(copeidrighttbl)
```

#### Output
```lua
	tbl = {"123", "666", "789"}
	copiedwrongtbl = {"123", "666", "789"}
	copiedrighttbl = {"123", "456", "789"}
```

*At least I think that is how it should work, if you're interested iirc its because tables are passed around as pointers. So copiedwrongtbl is equal to tbl and essentialy point to the same place. Might be wrong someone can correct me on that*