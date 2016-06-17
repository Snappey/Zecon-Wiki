
## Chatbox

[TOC]

#### Description
Used to interact with the gamemodes custom chatbox and where the chatbox elements are created and defined.

#### File Structure
* cl_chatbox.lua
* sv_chatbox.lua

##### cl_chatbox.lua
	
* [chat.AddText](Clientside/chat.AddText) 
* [cityrp.chatBox.chatText](Clientside/cityrp.chatBox.chatText)
* [cityrp.chatBox.createDermaAll](Clientside/cityrp.chatBox.createDermaAll)
* [cityrp.chatBox.createDermaButton](Clientside/cityrp.chatBox.createDermaButton)
* [cityrp.chatBox.createDermaButtons](Clientside/cityrp.chatBox.createDermaButtons)
* [cityrp.chatBox.createDermeCheckBox](Clientside/cityrp.chatBox.createDermeCheckBox)
* [cityrp.chatBox.createDermaCheckBoxes](Clientside/cityrp.chatBox.createDermaCheckBoxes)
* [cityrp.chatBox.createDermaFilters](Clientside/cityrp.chatBox.createDermaFilters)
* [cityrp.chatBox.createDermaPanel](Clientside/cityrp.chatBox.createDermaPanel)
* [cityrp.chatBox.createDermaTextEntry](Clientside/cityrp.chatBox.createDermaTextEntry)
* [cityrp.chatBox.explodeByTags](Clientside/cityrp.chatBox.explodeByTags)
* [cityrp.chatBox.getPosition](Clientside/cityrp.chatBox.getPosition)
* [cityrp.chatBox.getSpacing](Clientside/cityrp.chatBox.getSpacing)
* [cityrp.chatBox.getX](Clientside/cityrp.chatBox.getX)
* [cityrp.chatBox.getY](Clientside/cityrp.chatBox.getY)
* [cityrp.chatBox.messageAdd](Clientside/cityrp.chatBox.messageAdd)
* [cityrp.chatBox.printConsole](Clientside/cityrp.chatBox.printConsole)
* [cityrp.replacecodes](Clientside/cityrp.replacecodes)
* [table.copy](Clientside/table.copy)

##### sv_chatbox.lua

* [cityrp.chatBox.add](Serverside/cityrp.chatBox.add)
* [cityrp.chatBox.addInRadius](Serverside/cityrp.chatBox.addInRadius)

#### Information

* Two hooks are exposed by this library

```lua
	hook.Call("OpenChatBox", GAMEMODE)
	hook.Call("CloseChatBox", GAMEMODE)
```