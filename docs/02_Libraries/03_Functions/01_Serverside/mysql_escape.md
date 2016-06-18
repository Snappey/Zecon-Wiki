
## mysql_escape

```lua
mysql_escape(string str)
```

#### Arguments

**string sql** - SQL Query to escape

#### Returns

**string escapedsql** - Escaped SQL Query

#### Description
Escapes `\\`, `'` and `"` in the provided string.

#### Information
* Needs checking
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_functions.lua#ln7)

#### Examples
```lua
	print(mysql_escape("testing' 123"))
```

#### Output
```lua
	"testing\' 123"
```
