---
title: "Counter-Strike: Global Offensive (CSGO)"
description: CSGO Widget Configuration
layout: ../../../layouts/MainLayout.astro
---

Widget for [Counter-Strike: Global Offensive (CSGO) Server](https://developer.valvesoftware.com/wiki/Counter-Strike:_Global_Offensive/Dedicated_Servers).\
It use [gamedig](https://www.npmjs.com/package/gamedig) library to get game's server informations.\
You can use `counter-strike-global-offensive.png` or `counter-strike-2.png` as icon.

Allowed fields: `["map", "players", "maxplayers", "ping"]`.

```yaml
widget:
    type: csgo
    url: udp://csgoserver.host.or.ip:port
```

<img alt="CSGO Widget" src="https://user-images.githubusercontent.com/18687289/254726254-b980ffc4-049d-4d1d-b11c-5070a7f5845d.png">

*Added in v0.6.24*
