
## msg_admins

```lua
msg_admins(string msg)
```

#### Arguments

**string msg** - Message to be sent to to the admins

#### Description
Sends a message to all admins on the server.

#### Information
* Loops through all players and checks if they are an admin, then sends them the message.
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_functions.lua#ln15)

#### Examples
```lua
	msg_admins("Hello Admins!")
```

#### Output
```lua
	"Hello Admins" -- In admins chatbox
```
