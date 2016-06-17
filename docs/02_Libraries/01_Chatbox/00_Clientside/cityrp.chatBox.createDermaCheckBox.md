
## cityrp.chatBox.createDermaCheckBox

```lua
cityrp.chatBox.createDermaCheckBox(string name, string convar, number x, string tooltip, string label, Panel parent, number y)
```

#### Arguments

**string name** - Name of the checkbox (Used as an index for the table)

**string convar** - ConVar to tie the checkbox to

**number x** - X coordinate to place the checkbox (relative to parent)

**string tooltip** - Text that is displayed when hovered over

**string label** - Text that is displayed next to checkbox

**Panel parent** - Panel to parent the checkbox to.

**number y** - Y coordinate to place the checkbox (relative to parent)

#### Description
Used to create checkboxes for the chatbox.

#### Information
* Called internally by cityrp.chatBox.createDermaCheckboxes()
* Primarily used in the gamemode to filter messages out of player chatboxes
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/cl_chatbox.lua#ln259)


#### Examples
```lua
	cityrp.chatBox.createDermaCheckBox("OOC", "cityrp_chatbox_ooc", 8, "Filter out-of-character messages.", "Filter OOC", cityrp.chatBox.derma.filters, 8);
```
