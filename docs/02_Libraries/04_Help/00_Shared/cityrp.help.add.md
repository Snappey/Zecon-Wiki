
## cityrp.help.add

```lua
cityrp.help.add(string category, string help, string tip, string(?) command  )
```

#### Arguments

**string category** - Category to insert or add the command to.

**string help** - Help message to go with the category <optional>

**string tip** - Tip for using a command associated with the help message <optional>

**string command** - Name of the command with prefix associated with the help <optional>

#### Description
Is used to add messages to the F1 Help Menu, can be used in a vareity of ways. By only including the `category` argument it creates a title. By only including the the first two arguments it inserts the help message into the first category.

#### Information
* Used to create the list of commands and rules in the F1 Menu.
* All added values are stored in a table and cached `cityrp.help.stored`
* This function networks the values to the client during the call.
* [Srouce](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_help.lua#ln17)

#### Examples
```lua
	cityrp.help.add("General");
	cityrp.help.add("General", "Using any exploits will get you banned permanently.");
```

#### Output
```lua
	"Inserts the General Category"
	"Adds 'Using any exploits will get you banned permanently.' to the general category"
```
