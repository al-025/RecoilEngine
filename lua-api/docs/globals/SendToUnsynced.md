---
layout: default
title: SendToUnsynced
parent: Lua API
permalink: lua-api/globals/SendToUnsynced
---

{% raw %}

# global SendToUnsynced

---

```lua
function SendToUnsynced(...: (boolean|number|string)?)
```
@param `...` - Arguments. Typically the first argument is the name of a function to call.







Invoke `UnsyncedCallins:RecvFromSynced` callin with the given arguments.

[<a href="https://github.com/beyond-all-reason/RecoilEngine/blob/0683321af751bf99a7fe3fc28f5e1ca76b80c591/rts/Lua/LuaHandleSynced.cpp#L1966-L1972" target="_blank">source</a>]


{% endraw %}