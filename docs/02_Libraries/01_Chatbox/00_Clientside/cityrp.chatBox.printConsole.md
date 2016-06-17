
## cityrp.chatBox.printConsole

```lua
cityrp.chatBox.printConsole(table message)
```

#### Arguments

**table message** - Message table structure 

```lua
message = {
	title = {
	[1] = string prefix
	[2] = Color color
	},
	name = {
	[1] = string name
	[2] = Color color
	},
	icon = {
	[1] = string iconpath
	[2] = string iconascii
	},
	blocks = {
	[1-99] = string message
	}
}
```

#### Description
This is used to print a chat message into the local players console, used for echoing chat into console.

#### Information
* all the inner tables of message are not required apart from `message.blocks`
* This is called in cityrp.chatBox.addMessage()
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/cl_chatbox.lua#ln568)

#### Examples
```lua
	cityrp.chatBox.printConsole({
		blocks = {
			"testing",
			"123",
			"543",
			"345"
		}
	})
```

#### Output
```lua
	testing 123 543 345
```
*Hasnt been properly testing, and Im not 100% sure this is correct*
