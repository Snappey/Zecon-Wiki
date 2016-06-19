
## cityrp.team.add

```lua
cityrp.team.add(string name, Color color, table males, table females, string description, number salary, number limit, string access, string(?) blacklist, table canmake )
```

#### Arguments

**string name** - Name of the job

**Color color** - Colour of the job

**table male** - Table of male models

**table females** - Table of female models

**string description** - Description of the job

**number salary** - Salary of the job

**number limit** - Maximum amount of the job at any one time

**string access** - Access string (e.g. for donators only)

**string(?) blacklist** - Not sure how this is formatted

**table canmake** - What can the job manufacture 

#### Returns

**number jobindex** - Index of the job

#### Description
Used to add jobs to the gamemode, they are also registered through the `team` library from the base gamemode and registered in the cityrp table `cityrp.team.stored`

#### Information
* Some arguments can be missed out or passed as nil, and they will default to a value (Check source code for those values)
* Not sure how blacklist should be formatted to work correctly, think its the string it uses when blacklisting someone but not 100% sure.
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_team.lua#ln11)

#### Examples
```lua
	TEAM_PRESIDENT = cityrp.team.add("President", Color(255, 50, 25, 200), "models/mayor1.mdl", "models/mayor2.mdl", "Runs the city and keeps it in shape.", 500, 1, "n", true, {"Vehicles", "Misc.", "Clothing", "Packaging", "Mixtures"});

	print(TEAM_PRESIDENT)
```

#### Output
```lua
	1
```
