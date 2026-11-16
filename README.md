# Craftopia Academia — Server Resource Pack

Custom icons for every Quirk (51), every ability and skill-tree move (765) the Quirk Focus and the Quirk Factor Vial,
plus the Craftopia Academia title screen, splash texts and pack icon. Minecraft Java **1.21.11** (pack format 75).

## Server setup (`server.properties`)

```
resource-pack=https://raw.githubusercontent.com/furydenoo/mha-legacy-resource-pack/53ca05a54ddd29bb6bc59b82c816c3b1a9da243c/MHALegacy-ResourcePack.zip
resource-pack-sha1=f9d6b0c5ab99e7c5bd39822288d30f67de887379
require-resource-pack=true
resource-pack-prompt={"text":"Craftopia Academia server pack","color":"gold"}
```

Every time the zip changes, update `resource-pack-sha1` (players re-download when it changes) and point
`resource-pack` at that commit (`.../<commit hash>/MHALegacy-ResourcePack.zip`): the `main` link can serve an
old copy for a few minutes after a push, and a pinned link never does.

The title screen / splashes only show if a player installs the zip in their own `resourcepacks` folder.

`server-icon.png` goes in the server's main folder (server-list icon).
