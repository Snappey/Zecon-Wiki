
## cityrp.chatBox.add

```lua
cityrp.chatBox.add(CRecipientFilter recipientFilter, Player player, string filter, string text)
```

#### Arguments

**CRecipientFilter recipientFilter** - RecipientFilter used to determine who should receive the chat messages <optional>

**Player player** - Person who sent the message <optional> 

**string filter** - Filter to be applied on the clientside e.g. "ooc" or "yell"

**string text** - The message to be sent

#### Description
Used to broadcast the message from the server to all clients. Receiving clients can be filtered, if a filter is not passed it will be sent to all players regardless.

#### Information
* Player or RecipientFilter do not need to be passed for this to function
* Could probably be updated to use net messages, though Im not too sure if that will have any peformance difference
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_chatbox.lua#ln9)

#### Examples
```lua
	cityrp.chatBox.add(nil, Entity(1), "ooc", "Hello")
```

#### Output
```lua
	(OOC) Spai: Hello
```
