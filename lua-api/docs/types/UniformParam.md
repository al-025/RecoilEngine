---
layout: default
title: UniformParam
parent: Lua API
permalink: lua-api/types/UniformParam
---

{% raw %}

# class UniformParam


- supers: { , [string]: (T|T[]) }




A table of uniform name to value.

The Uniforms are the values you send along with the shader-program. To use
them in the shader-program declare them like this: `uniform float frame;`

Specify a Lua array to initialize GLSL arrays.

The engine will automatically fill in an appropriately named uniform for team
colour if it is declared;

```glsl
uniform vec4 teamColor;
```

[<a href="https://github.com/beyond-all-reason/RecoilEngine/blob/0683321af751bf99a7fe3fc28f5e1ca76b80c591/rts/Lua/LuaShaders.cpp#L552-L568" target="_blank">source</a>]







---




{% endraw %}