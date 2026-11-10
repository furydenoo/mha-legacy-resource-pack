# My Hero Academia: Legacy — Server Resource Pack

Custom icons for every Quirk (51), every ability and skill-tree move (765) and the Quirk Focus,
plus the MHA: Legacy title screen, splash texts and pack icon. Minecraft Java **1.21.11** (pack format 75).

## Server setup (`server.properties`)

```
resource-pack=https://raw.githubusercontent.com/furydenoo/mha-legacy-resource-pack/main/MHALegacy-ResourcePack.zip
resource-pack-sha1=c208dd08164360fa36d43ebbeaf994443f2b0d86
require-resource-pack=true
resource-pack-prompt={"text":"MHA: Legacy server pack","color":"gold"}
```

Every time the zip changes, update `resource-pack-sha1` (players re-download when it changes).

The title screen / splashes only show if a player installs the zip in their own `resourcepacks` folder.

`server-icon.png` goes in the server's main folder (server-list icon).
