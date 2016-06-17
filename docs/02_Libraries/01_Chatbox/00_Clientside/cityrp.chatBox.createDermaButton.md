
## cityrp.chatBox.createDermaButton

```lua
cityrp.chatBox.createDermaButton(string name, string text, number x, number width, string toolTip, function doClick, function think)
```

#### Arguments
**string name** - Name of the button (Index for the table)

**string text** - Text to display on button

**number x**  - Sets the X coordinate of the button (Parented to the chatbox panel)

**number width** - Sets the width of the button

**string toolTip** - Text that appears when they hover over the button

**function doClick** - Called when the button is clicked

**function think** - Called every tick while the button is active

#### Description
Used to create buttons for the chatbox, is parented directly to the chatbox.

#### Information
* All of the buttons used in the chatbox are defined through this function
* Called internally by cityrp.chatBox.createDermaButtons()
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/cl_chatbox.lua#ln241)

#### Examples
```lua
    cityrp.chatBox.createDermaButton("Down", "-", 454, 16, "Scroll down the message area.", function()
        cityrp.chatBox.history.position = cityrp.chatBox.history.position + 1;
    end, function(self)
        if (cityrp.chatBox.history.messages[cityrp.chatBox.history.position + 1]) then
            self:SetDisabled(false);
        else
            self:SetDisabled(true);
        end;
    end);
```
