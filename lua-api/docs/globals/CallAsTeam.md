---
layout: default
title: CallAsTeam
parent: Lua API
permalink: lua-api/globals/CallAsTeam
---

{% raw %}

# global CallAsTeam

---

```lua
function CallAsTeam(
  teamID: integer,
  func: fun(...),
  ...: any
) -> The any ...
```
@param `teamID` - Team ID.

@param `func` - The function to call.

@param `...` - Arguments to pass to the function.


@return `The` - return values of the function.






Calls a function from given team's PoV. In particular this makes callouts obey that team's visibility rules.

[<a href="https://github.com/beyond-all-reason/RecoilEngine/blob/0683321af751bf99a7fe3fc28f5e1ca76b80c591/rts/Lua/LuaHandleSynced.cpp#L2333-L2340" target="_blank">source</a>]


{% endraw %}