
## cityrp.zones.get

```lua
cityrp.zones.get(Player player)
```

#### Arguments

**Player player** - Player to check zone

#### Returns

**string Level1** - Top level area the player is in

**string Level2** - Second level area the player is in

**string Level3** - Third level area the player is in


#### Description
Gets the players area location on the map in 3 levels with increasing detail. For example top level: `City`, second level: `Nexus` and third level: `Lobby`.

#### Information
* Only supports a max of 3 layers of zones
* You are not guaranteed to get a string as a return value if the player is not found inside a box, instead the value will be nil. (This applies to all return values)
* [Source](https://app.assembla.com/spaces/roleplaygamemode/subversion/source/HEAD/gamemode/core/libraries/sh_zones.lua#ln20)

#### Examples
```lua
	print( cityrp.zones.get(Entity(1)) )
```

#### Output
```lua
	City, Nexus, Lobby
```
