
## Hook

[TOC]

#### Description
Implements a new interface for hooks within the cityrp gamemode. Allows for the creation of hooks without UniqueIDs and the massremoval of hooks with similar tags.

#### File Structure
* sh_hook.lua
##### sh_hook.lua
	
* [cityrp.hook.add](Hooks/Shared/cityrp.hook.add)
* [cityrp.hook.remove](Hooks/Shared/citrp.hook.remove)
* [cityrp.hook.removeAll](Hooks/Shared/cityrp.hook.removeAll)
* [cityrp.hook.removeTagged](Hooks/Shared/cityrp.hook.removeTagged)

#### Information

* Everything in this library is disabled and does nothing but decrease peformance apart from `cityrp.hook.add`
* So basically you can only add hooks but you cant remove them
* Not sure who disable them or why, but it came with our version