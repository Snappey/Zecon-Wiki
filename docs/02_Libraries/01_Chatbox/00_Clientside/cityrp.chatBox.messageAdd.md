
## cityrp.chatBox.messageAdd
```lua
cityrp.chatBox.messageAdd(table title, table name, table text, bool filtered, table icon)
```
*Lots of fucking tables for some reason*

#### Arguments

**table title** - Table used to prefix message `{prefix, <colour>}` e.g. `{(OOC)}`

**table name** - Table used to name message `{name, <colour>}` e.g. `{"Spai"}`

**table text** - Table with the main message `{message, <colour>}` e.g. `{"Hello!"}`

**bool filtered** - Whether the message is being filtered or not e.g. in `OOC` or `IC`

**table icon** - What icon is being used with the message `{iconpath, asciiversion}` e.g. `{"icon16/door_in", "->[]"}`

#### Description
This is used to print chat messages into the players chatbox, tables that feature `<colour>` have an optional colour attribute which allow you to change the texts colour,
if no colour is chosen it will default to White.

#### Information
* Used internally by cityrp.chatBox.chatText()
* Would recommend using cityrp.chatBox.chatText instead of this function, as you'll be skipping alot of checks including formating / filters.
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/cl_chatbox.lua#ln568)


#### Examples
```lua
	cityrp.chatBox.messageAdd( {"(OOC)"}, {"Console", Color(150, 150, 150, 255) }, {"This is ran from console!"}, false);
```

#### Output
```lua
	(OOC) (*IsYellow* ->)Console: This is ran from console!
```
