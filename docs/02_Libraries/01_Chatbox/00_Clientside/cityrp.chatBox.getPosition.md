
## cityrp.chatBox.getPosition

```lua
 cityrp.chatBox.getPosition()
```

#### Returns

**number x** - X coordinate of the chatbox 

**number y** - Y coordinate of the chatbox

#### Description
Returns the position of the chatbox on the screen.

#### Information
* If there is no custom chatbox position, just does the following: then returns x and y
```lua
local x, y = 8, ScrH() - (ScrH() / 4);
```

* Also accounts for custom chatbox positions
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/cl_chatbox.lua#ln91)

#### Examples
```lua
	local x,y = cityrp.chatBox.getPosition()
	print(x,y)
```

#### Output
```lua
	8, 1440
```
