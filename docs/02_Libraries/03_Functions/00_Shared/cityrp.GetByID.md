
## cityrp.GetByID

```lua
cityrp.GetByID(number id)
```

#### Arguments

**number ID** - The ID of the Player you want to find

#### Returns

**Player player** - If a matching ID is found, the resultant player is returned

**bool result** - If a matching ID is not found, the returned value is `false`

#### Description
Used to get a player object by using their UserID.

#### Information
* This could be optimised hugely by just using Player(UserID) instead of this function and looping through every player on the server
* Doesnt seem to be called at all though, so thats good
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_functions.lua#ln117)

#### Examples
```lua
	print(cityrp.GetByID(1):Nick())
```

#### Output
```lua
	Spai
```



