
## cityrp.help.playerInitialized

```lua
cityrp.help.playerInitialized(Player player)
```

#### Arguments

**Player player** - Player to send help table

#### Description
Sends the help table to the player when they have first Initialized.

#### Information
* Used internally and called via a hook `PlayerInitialized`, arguments are passed from the hook to the function.
* Function waits 2 seconds before calling, presumably waits till the player is actually valid before networking to them.
* On top of that [this](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_help.lua#ln139) no idea why that is done
* Help menu is also opened on the player when this function is called
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_help.lua#ln139)

#### Examples
```lua
	cityrp.help.playerInitialized(Entity(1))
```

#### Output
```lua
	-- Client receives help table from server
	-- F1 menu is opened with help being shown
```
