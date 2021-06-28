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
Change the server brand from Paper to whatever you want! This is shown on some clients/in the f3 menu.
### messages.remove-console-spam
Remove the console spam messages like Player_X went too fast!
### messages.hide-player-ips-from-console
Hide player ips from when players join your server.
### messages.hide-player-coords-from-console
Hide player coordinates from when players join your server.
### messages.remove-connection-messages-from-console
Removes the connection messages from console for when players join your server. This will not remove the messages ingame.
### messages.remove-player-command-messages-from-console
Hide player commands from console. Useful to hide messages/spam
~~### disable-chunk-loading
Disable all chunks being sent to the player. This is like the 2b2t queue where no chunks are sent to you. All you see is "Waiting for chunk..." Great for queue/auth servers where you want to limit bandwidth usage.~~ Will be added later. Use ccspigot in your auth/queue servers or a seperate limbo server.

## Changes from paper
~~### Autosave
The autosave is now using paper's instead of bukkit by default. This is a lot better.
This will only be used if you delete your paper.yml AND your bukkit.yml before using.~~ Will be added later, just manually set the autosave in paper.yml (follow my guide)
