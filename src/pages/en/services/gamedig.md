---
title: GameDig
description: GameDig Widget Configuration
layout: ../../../layouts/MainLayout.astro
---

Use [GameDig](https://www.npmjs.com/package/gamedig) library to get game's server informations.

Widget example for [Counter-Strike: Global Offensive (CSGO) Server](https://developer.valvesoftware.com/wiki/Counter-Strike:_Global_Offensive/Dedicated_Servers).\
You can use `counter-strike-global-offensive.png` or `counter-strike-2.png` as icon.

Allowed fields: `["status", "name", "map", "currentPlayers", "players", "maxPlayers", "bots", "ping"]`.

```yaml
widget:
    type: gamedig
    serverType: csgo # see https://github.com/gamedig/node-gamedig#games-list
    url: udp://server.host.or.ip:port
```

<img alt="GameDig Widget" src="https://github-production-user-asset-6210df.s3.amazonaws.com/18687289/256046577-f973503b-d309-493b-b88b-03a518c611bc.png">

*Added in v0.6.24*
