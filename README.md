# mc-cheat-sheet
# Outline
1. [General](#general)
2. [Installed Plugins](#installed-plugins)
3. [Potentially Interesting Plugins](#potentially)

# General<a name"general"></a>
- Colors: http://wiki.ess3.net/mc/
# Installed Plugins<a name="installed-plugins"></a>
- [Vault](#vault)
- [LuckPerms](#luck-perms)
- [EssentialsX](#essentialsx)
- [WorldEdit](#worldedit)
- [PlotSquared](#plotsquared)
- [Dynmap](#dynmap)

## [Vault](https://www.spigotmc.org/resources/vault.34315/)<a name="vault"></a>
> Vault is a Permissions, Chat, & Economy API to give plugins easy hooks into these systems without needing to hook or depend on each individual plugin themselves. It was born out of a distaste for how both Register and the current Permissions API are run, and their lack of features or over-complicated implementations. Vault attempts to solve these issues by being intuitive and providing plugins with support for any system that they may use.
- Version: 1.7.1

## [LuckPerms](https://www.spigotmc.org/resources/luckperms-an-advanced-permissions-plugin.28140/)<a name="luck-perms"></a>
> Description: LuckPerms is an advanced permissions implementation aiming to be a fast, reliable and flexible alternative to existing permission plugins. The project's main goals are centered around high performance and a wide feature set, filling the gaps of functionality and building upon existing features found in other plugins. LuckPerms also includes an extensive API for developers, and support for a variety of Minecraft server software & data storage options.
- Version: 4.3.64
- Build Server: https://ci.lucko.me/job/LuckPerms/
- Wiki: https://github.com/lucko/LuckPerms/wiki
- Commands: https://github.com/lucko/LuckPerms/wiki/Command-Usage


## [EssentialsX](https://www.spigotmc.org/resources/essentialsx.9089/)<a name="essentialsx"></a>
> EssentialsX is an unofficial continuation of Essentials, updated to support modern Minecraft and Spigot versions. It provides several performance enhancements and fixes that are currently not available in Essentials and Spigot-Essentials.
- Version: 2.15.0.60
- Components:
    - EssentialsX
    - EssentialsAntiBuild
    - EssentialsChat
    - EssentialsGeoIP
    - EssentialsProtect
    - EssentialsSpawn
- Commands: https://essinfo.xeya.me/commands.php
- Permissions: https://essinfo.xeya.me/permissions.php
- Requires: [Vault](#vault)

## [WorldEdit](https://dev.bukkit.org/projects/worldedit/files/2646337)<a name="worldedit"></a>
> Description: WorldEdit is an easy-to-use in-game world editor for Minecraft, supporting both single player and multiplayer.
- Version: 7.0.0 Beta 4
- Wiki: http://wiki.sk89q.com/wiki/WorldEdit
- Permissions: http://wiki.sk89q.com/wiki/WorldEdit/Permissions
- Commands: http://wiki.sk89q.com/wiki/WorldEdit/Permissions (yes the permissons page ;-) 
- Todo
    - [ ] Test

## [PlotSquared](https://www.spigotmc.org/resources/plotsquared.1177/)<a name="plotsquared"></a>
> PlotSquared is a land management plugin and world manager which also comes with several highly configurable world generators. You can create plots of land in existing worlds using plot clusters, or you can have a full world of plots.
- Version: 4.0-pre-release
- Requires: [WorldEdit](#worldedit)
- Wiki: https://github.com/IntellectualSites/PlotSquared/wiki
- Build Server: https://ci.athion.net/job/PlotSquared-Breaking/
- Todo
    - [ ] Test

## [Dynmap](https://www.spigotmc.org/resources/dynmap.274/)<a name="dynmap"></a>
> A Google Maps-like map for your Minecraft server that can be viewed in a browser. Easy to set up when making use of Dynmap's integrated webserver which works out-of-the-box, while also available to be integrated into existing websites running on Apache and the like. Dynmap can render your worlds using different renderers, some suitable for performance, some for high detail.
- Version: 3.0-beta-3
- Wiki: https://github.com/webbukkit/dynmap/wiki
- Commands: https://github.com/webbukkit/dynmap/wiki/Commands

## [Carz](https://www.spigotmc.org/resources/carz.56255/)<a name="carz"></a>
> Do you have a server that has a city theme? Want to add more realism by being able to drive a car on any surface? Then this is the perfect plugin for your server!
- Version: 6.2
- Permissions: https://dev.bukkit.org/projects/carz
- Todo
    - [ ] Set permissions for normal users
    - [ ] Test

# Potentially Interesting Plugins<a name="potentiually"></a>
- [ ] Plot2Dynmap https://www.spigotmc.org/resources/plot2dynmap.1292/ --> use [this release](https://github.com/IntellectualSites/plot2dynmap/releases)
- [ ] Lucky Block http://www.minecraftascending.com/projects/lucky_block/lucky_block.html
- [ ] SimplePets https://www.spigotmc.org/resources/simplepets.14124/
    - requires: SimpleAPI https://www.spigotmc.org/resources/simpleapi.24671/
- Clans https://www.spigotmc.org/resources/clans-clan-system-full-gui-commands.34696/
    - requires: PlaceholderAPI https://www.spigotmc.org/resources/placeholderapi.6245/
- Factions https://www.spigotmc.org/resources/factions.1900/
    - seems to be not stable on spigot 1.13.2