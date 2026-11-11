# Craftopia Academia — Server Resource Pack

Custom icons for every Quirk (51), every ability and skill-tree move (765) the Quirk Focus and the Quirk Factor Vial,
plus the Craftopia Academia title screen, splash texts and pack icon. Minecraft Java **1.21.11** (pack format 75).

## Server setup (`server.properties`)

```
resource-pack=https://raw.githubusercontent.com/furydenoo/mha-legacy-resource-pack/38d1f3ba9533088ffd22dc38040322cd34da051e/MHALegacy-ResourcePack.zip
resource-pack-sha1=49a6598e0b0f8ab73764176c50ea76c3b9eb7b47
require-resource-pack=true
resource-pack-prompt={"text":"Craftopia Academia server pack","color":"gold"}
```

Every time the zip changes, update `resource-pack-sha1` (players re-download when it changes) and point
`resource-pack` at that commit (`.../<commit hash>/MHALegacy-ResourcePack.zip`): the `main` link can serve an
old copy for a few minutes after a push, and a pinned link never does.

The title screen / splashes only show if a player installs the zip in their own `resourcepacks` folder.

`server-icon.png` goes in the server's main folder (server-list icon).
