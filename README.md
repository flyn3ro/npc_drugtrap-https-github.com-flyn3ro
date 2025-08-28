

````markdown
# npc_drugtrap

**NPC Drug Trap** — FiveM script featuring:
- NPC-triggered drug deal traps
- Automatic cuffing with animations
- Police dispatch alerts with map blip and waypoint
- Decision options: Fight / Flee / Submit
- Works with both **ESX** and **QBCore**

## Installation

1. Clone or download this repo into your FiveM `resources/` folder:
   ```bash
   git clone https://github.com/flyn3ro/npc_drugtrap.git
````

2. Add to your `server.cfg`:

   ```cfg
   start npc_drugtrap
   ```
3. Use `/dealnpc` near an NPC to test the scenario.

## Features

* Detects `ESX` or `QBCore` automatically.
* Plays cuff animation, freezes player, then alerts PD.
* Creates police blip and sets waypoint to incident location.
* Allows player to **fight**, **flee**, or **submit** after cuffing.

## Customization Tips

* Replace notifications with your server's preferred system.
* Swap in different animations or UI menus like NUI for decisions.
* Integrate deeper into your dispatch or jail systems.

---


