# Advanced Fireworks

###[CLICK HERE TO DOWNLOAD THE LATEST RELEASE.](https://github.com/Basssiiie/Advanced-Fireworks/releases)

This is a small SA-MP script that allows players to spawn and fire fireworks in the server.

This script "requires" the Streamer Plugin, which you can download **[here](http://forum.sa-mp.com/showthread.php?t=102865)**. If you really don't want to use the Streamer Plugin, you can download the source code and set the USE_STREAMER value to false. Recompile it and the script will use the default SA-MP functions. 

To see the script in action, you can watch this video from 2011: https://www.youtube.com/watch?v=lm9dfnIMN2U

## How to add to server

**Step 1:** Download the latest release from the link at the top of this document.

**Step 2:** Drop the `*.pwn` and `*.amx` files into the `filterscripts` folder in your server folder.

**Step 3:** Add `AdvancedFireworks` to your `filterscripts` line in the `server.cfg` file, which is located in your main server folder.

## Commands
| Command | Effect |
| --- | --- |
| `/firework` | Opens the fireworks menu. |
| `/fireworks` | Same as `/firework`. |

After the player put down the first firework item, they will get a detonator to start the show. The player can also put down more firework items to make a bigger show.
