
## cityrp.chatBox.createDermaPanel

```lua
cityrp.chatBox.createDermaPanel()
```

#### Description
Creates the main derma panel, which all other chatbox elements are parented too.

#### Information
* Is the first function to be called by cityrp.chatBox.createDermaAll
* Panel created is "EditablePanel"
* Can only be once
* Exposes two hooks to be used

	`hook.Call("OpenChatBox", GAMEMODE);`

	`hook.Call("CloseChatBox", GAMEMODE);`

* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/cl_chatbox.lua#ln407)
