
## cityrp.chatBox.wrapText

```lua
cityrp.chatBox.wrapText(string text, string font, number width, number overhead, table base  )
```

#### Arguments

**string text** - The text to use for wrapping

**string font** - Font used by the text

**number width** - Max width of the text

**number overhead** - How much width is lost from other elements

**table base** - Table to insert our values 

#### Description
Used to wrap text in the chatbox, prevents text from reaching the end of the element and carrying on out of vision.

#### Information
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/cl_chatbox.lua#ln124)

#### Examples
```lua
	local wrapped = {} -- Where our wrapped text is stored
	cityrp.chatBox.wrapText("This is a test message", "cityrp_chatBox_MainText", 576, 150, wrapped);
	PrintTable(wrapped)
```

#### Output
```lua
wrapped = {
	[1] = "This is a test message"
}
```
*If the message is longer I think it wraps into a 2nd value in the table, provided its longer than the width - overhead ofc*