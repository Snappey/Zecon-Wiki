
## cityrp.chatBox.chatText
```lua
cityrp.chatBox.chatText(number index, string name, string text, string filter)
```

#### Arguments
**index** - Player Index

**name** - Name of the Player

**text** - Text to be added

**filter** - Type of chat (e.g. 'arrested' or 'ooc')

#### Description
Called when the player chats locally or when a message is received from the server. Is used to display messages in chat with the relevant
formatting, colour and icons.                      

#### Information
* Used by the chatbox to display player rank icons. (Superadmin, Developer etc.)
* Chat formatting for OOC, LOOC and adverts are called in this function.
* This function passes it result onto chat.chatBox.messageAdd (note: reference wiki page)
* At the time of writing there are a few steamids [checks](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/cl_chatbox.lua#ln934) for rank icons.
	
    (STEAM_0:0:5119023, STEAM_0:1:15472195)
* [Source Link](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/cl_chatbox.lua#ln901)

#### Examples

```lua 
cityrp.chatBox.chatText(1, "Spai", "Yoski Broski", "ooc")
```

##### Output

```lua
[Wrench Icon] (OOC) Spai: Yoski Broski
```