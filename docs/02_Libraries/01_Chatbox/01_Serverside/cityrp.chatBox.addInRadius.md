
## cityrp.chatBox.addInRadius

```lua
cityrp.chatBox.addInRadius(Player player,CRecipientFilter filter, Vector position, number radius)
```

#### Arguments

**Player player** - Player who sent the message

**CRecipientFilter filter** -- Filter determines who should receive the message being sent

**Vector position** -- Position that the radius check should be compared too

**number radius** -- Radius of the message to be sent

#### Description
Sends a message to all players with the defined radius.

#### Information
* Calls cityrp.chatBox.add for each player found inside the radius instead of making a table and calling the function with all the players once?
* Calls g_Player.GetAll() instead of player.GetAll()?
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sv_chatbox.lua#ln25)


#### Examples
```lua
	cityrp.chatBox.addInRadius(Entity(1), "ooc", "This is a test", Entity(1):GetPos(), 256)
```

#### Output
```lua
	(OOC) Spai: This is a test
```
*And everyone within 256 units of me will also see the message*