---
layout: default
title: LogLevel
parent: Lua API
permalink: lua-api/types/LogLevel
---

{% raw %}

# alias LogLevel
---



```lua
(alias) LogLevel = (integer|"debug"|"info"|"notice"|"warning"|"deprecated"|"error"|"fatal")
    | integer
    | "debug" -- LOG.DEBUG
    | "info" -- LOG.INFO
    | "notice" -- LOG.NOTICE (engine default)
    | "warning" -- LOG.WARNING
    | "deprecated" -- LOG.DEPRECATED
    | "error" -- LOG.ERROR
    | "fatal" -- LOG.FATAL

```




[<a href="https://github.com/beyond-all-reason/RecoilEngine/blob/0683321af751bf99a7fe3fc28f5e1ca76b80c591/rts/Lua/LuaUtils.cpp#L1430-L1440" target="_blank">source</a>]


{% endraw %}