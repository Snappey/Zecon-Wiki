
## chat.AddText 

```lua
chat.AddText( vararg args )
```

#### Description
Used to add text to the local players chatbox, only this player can see the text.
#### Information 
* This overrides Garrys Mods default [chat.AddText](http://wiki.garrysmod.com/page/chat/AddText) function, removing the use of colours.
* A Player object can be used, this will append their name to the string. (See Example Below)
* [Source Link](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/cl_chatbox.lua#ln7)
#### Examples

```lua
chat.AddText("Testing ", " 123 ", " 456 ")

chat.AddText("Hello ", LocalPlayer())
```

#### Output

```lua
"Testing 123 456 "

"Hello Spai"
```
