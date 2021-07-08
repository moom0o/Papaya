[![Discord Mine](https://img.shields.io/discord/807380182729228298?label=chat&logo=discord&logoColor=white)](https://discord.gg/vsmnEcCSsn)

# Papaya

A paper fork/1.12 continuation that aims to prevent skylight lag, allow changing the server brand, and more.
<br>
If you want to patch more exploits other than these use my bukkit plugin https://github.com/moom0o/AnarchyExploitFixes
<br>

## Config options

These options are in papaya.yml.

### settings.max-light-time

Max time for light updates, wont perform light updates if it takes too long. Patches the popular skylight lag exploit :)

### settings.server-brand

Change the server brand from Papaya to whatever you want! This is shown on some clients/in the f3 menu.

### messages.remove-console-spam

Remove the console spam messages like Player_X went too fast!

### messages.hide-player-ips-from-console

Hide player ips from when players join your server.

### messages.hide-player-coords-from-console

Hide player coordinates from when players join your server.

### messages.remove-connection-messages-from-console

Removes the connection messages from console for when players join your server. This will not remove the messages
ingame.

### messages.remove-player-command-messages-from-console

Hide player commands from console. Useful to hide messages/spam

### settings.prevent-chunks-generating-past-worldborder-lag-exploit

Prevent chunks from generating past the world border. Chunks generating past world border seem to cause lots of lag
problems.

### settings.chunk-dupe

Allow or disallow the chunkdupe

### settings.pathfinder.goal-selection-delay

the time in ticks the pathfinding waits until it calculates a new goal, the higher its set, the less often mobs get new
pathing instructions

### settings.chunks.prevent-chunks-from-loading

Prevent chunks from loading completely, great for auth/queue/limbo servers.

### backports.allow-perm-block-break-exploits

Set true to allow players to break indestructible blocks with exploits, recommended to leave this as false!

backported from paper

- https://github.com/PaperMC/Paper/commit/c2f8d1ef98580daaba71d0fc9a4f37ed072052cc
- https://github.com/PaperMC/Paper/commit/3e75d908100814a2d6ce0bf94fecf0d4eda5a22b