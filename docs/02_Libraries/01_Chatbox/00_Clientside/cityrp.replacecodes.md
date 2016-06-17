
## cityrp.replacecodes

```lua
cityrp.replacecodes(string str)
```

#### Arguments

**string str** - The string to replace codes for

#### Returns

**string str** - New string with replaced codes

#### Description
This function replaces strings in messages with values defined within the function, if it finds a match it will replace it with the variables defined below. The escape codes also require the user to be looking at another player to work correctly.

Escape Codes:


	%%t = UserID
	%%tn = Name
	%%tnn = RPName
	%%me = LocalPlayer-UserID
	%%men = LocalPlayer-UserName

#### Information
* Is called when the user is sending their message to the server to be broadcasted.
* Weridly incosisntent naming, could probably be optimised
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/cl_chatbox.lua#ln124)

#### Examples
```lua
	local str = cityrp.replacecodes("My name is %%men")
	print(str)
```

#### Output
```lua
	"My name is Spai"
```
