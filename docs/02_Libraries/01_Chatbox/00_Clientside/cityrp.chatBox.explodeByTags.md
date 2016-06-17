
## cityrp.chatBox.explodeByTags

```lua
cityrp.chatBox.explodeByTags(string variable, string seperator, string open, string close)
```

#### Arguments

**string variable** - String to explode

**string seperator** - String to use as a seperator

**string open** - Character where the string should start exploding

**string close** - Character where the string should stop exploding

#### Returns

**table results** - Exploded strings

#### Description
Takes a string and starts spliting it when the `open` variable is found, after that the results are then split up by the `seperator`
variable untill the `close` tag is reached when the variable stops exploding. This can happen multiple times in the same string, and will loop the entire length of the string

#### Information
* Not actually used anywhere inside cl_chatbox.lua where it is found
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/cl_chatbox.lua#ln867)


#### Examples
```lua
	local tbl = cityrp.chatBox.explodeByTags("Pro DarkRP | New and fresh| Staffed and we've got FASTDL", " ", "|", "|")
	PrintTable(tbl)
```

#### Output
```lua
	tbl = {
	[1] = "New"
	[2] = "and"
	[3] = "Fresh"
	}
```
*Needs to be checked, did this all in my head could be wrong*
