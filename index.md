---
title: LGX
uid: EVA / LGX
type: drive
badges:
    - Official
contributors: 
    - pkucmus
repo_url: https://github.com/EVA-3D/eva-lgx
cad_url: https://cad.onshape.com/documents/d2a2f19b34851a8570487add/w/1ff9bb9662c715a9cdc3d984/e/f74cb56cf915933a84ff4023
satisfies:
    - drive
---

# LGX

![preview](assets/LGX.png)

!!! info "Universal EVA Front"

    This drive uses the universal face, which means it's comatible with all hotends you can find in the Hotends section.

??? Question "What about LGX For Flexibles Set?"

    I'm working on it :)

### Bill of materials


=== "MGN12"

    <add-bom-button name="{{ meta.uid }} (MGN12)">
        {{ bom_to_json("LGX.MGN12.csv") }}
    </add-bom-button>
    
    {{ bom_to_md_table("LGX.MGN12.csv", 4) }}


=== "MGN15"

    <add-bom-button name="{{ meta.uid }} (MGN15)">
        {{ bom_to_json("LGX.MGN15.csv") }}
    </add-bom-button>
    
    {{ bom_to_md_table("LGX.MGN15.csv", 4) }}


#### PTFE Tube lenghts

| Hotend | Length |
| ------ | ------ |
| Mosquito | 30.4 mm |
| E3D V6 | 46.9 mm |
| Dragon | 31.9 mm |
| Copperhead | 45.9 mm |

### Links

{{ eva_download_button() }}

{{ repo_url }}

{{ cad_url }}
