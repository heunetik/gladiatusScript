# **gladiatusScript**
A Tampermonkey script for Gladiatus automatization

## Note:
- This script is no longer actively developed. All development has shifted towards a Chrome extension, which includes the full functionality of this script.
- The script has been updated on 08-11-2019 to ensure that the PvE features still work.
- Since the dungeons' version keeps getting updated, I've added an easy way to keep it up to date. If the script keeps refreshing on the dungeon page, it means that there was an update. All you have to do is to `right click -> inspect element` on the dungeon map, and copy the numbers from the `src` tag. e.g.: `src="9357/img/spacer.gif"` means that the `dungeonVersion` should be set to `9357`.
+ All other configuration is also done by hand, by modifying the same settings variable:
  + dungeonVersion - Set the current dungeon version
  + minHp - The HP limit - Above the limit you attack, under the limit you try to heal, if you have any available food (`1 - 100`)
  + upgradeSkills - toggle automatic upgrading (`true / false`),
  + expeditionsAttack - toggle automatic attack(`true / false`)
  + dungeonAttack - toggle automatic attack (`true / false`)
  + circusTurmaAttack - toggle automatic attack (`true / false`)
  + arenaAttack - toggle automatic attack (`true / false`)
  + mobGroupPosition & mobPosition: see attached photo

---
![Mob Settings](https://i.imgur.com/rSJOxzV.png)
![Dungeon Settings](https://i.imgur.com/bSuFQgA.png)

---

## **Features**
### Automatization
+ **PvE**
  + Expeditions
  + Dungeons
+ **PvP**
  + Arena - *not guaranteed to work*
  + Circus Turma - *not guaranteed to work*
+ **Skills**
  + Automatic skillpoint spending