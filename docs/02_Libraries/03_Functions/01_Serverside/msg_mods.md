
## msg_mods

```lua
msg_mods(string msg)
```

#### Arguments

**string msg** - Message to send to the mods

#### Description
Sends a message to all mods on the server.

#### Information
* Functionally the same as `msg_admins` however checks for mods instead.
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_functions.lua#ln24)

#### Examples
```lua
	msg_mods("Yo mods")
```

#### Output
```lua
	"You mods" -- In all mods chatbox
```
