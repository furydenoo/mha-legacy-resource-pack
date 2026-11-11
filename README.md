# Craftopia Academia — Server Resource Pack

Custom icons for every Quirk (51), every ability and skill-tree move (765) the Quirk Focus and the Quirk Factor Vial,
plus the Craftopia Academia title screen, splash texts and pack icon. Minecraft Java **1.21.11** (pack format 75).

## Server setup (`server.properties`)

```
resource-pack=https://raw.githubusercontent.com/furydenoo/mha-legacy-resource-pack/main/MHALegacy-ResourcePack.zip
resource-pack-sha1=79ec54125de2ea4db91691279a80bd083d84a798
require-resource-pack=true
resource-pack-prompt={"text":"Craftopia Academia server pack","color":"gold"}
```

Every time the zip changes, update `resource-pack-sha1` (players re-download when it changes).

The title screen / splashes only show if a player installs the zip in their own `resourcepacks` folder.

`server-icon.png` goes in the server's main folder (server-list icon).
