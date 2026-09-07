# Discord Rich Presence for Anki (AnkiDiscord)

### Description
This add-on will link Anki to Discord using Rich Presence.
It will show what you are currently doing on Anki (Main menu, browsing, adding or reviewing).
It will also show how many cards you have due, how many you have done today and how long you've been on Anki for.


A great way to share your progress with friends or motivate each other online

*Please rate and review this on [AnkiWeb](https://ankiweb.net/shared/info/1133851639)*


### Appearance
![What it looks like in discord](https://raw.githubusercontent.com/Monacraft/AnkiDiscord/master/preview.png)

### Installation 
[Here is our page on AnkiWeb](https://ankiweb.net/shared/info/1133851639)

Alternatively you can directly install us inside anki using the add-on code: **1133851639**

### Linux note
This add-on talks to Discord over its local IPC socket (`discord-ipc-N`), found in both `$XDG_RUNTIME_DIR` and `/tmp`, so it works with vanilla Discord, snap/flatpak builds, and modded clients like Vesktop.
If you use a client such as Vesktop, make sure Rich Presence is enabled first: Settings → Vencord → Vesktop → Miscellaneous → `arRPC`.

### Planned Features
 - Adding settings to configure how Anki is displayed on Discord
 - Adding other trackers such as streak (in days), average daily reviews, total mature cards etc.

### Update Log
 - 2.2: Fixed Rich Presence on Linux - Discord IPC socket is now found in both $XDG_RUNTIME_DIR (snap, flatpak and modded clients like Vesktop) and $TMPDIR (vanilla Discord)
 - 2.1: Clear the Discord presence when Anki closes instead of leaving it stuck
 - 2.0: Support for new version of Anki, switch to pypresence, fix of all bugs in 1.1
 - 1.1: Fixed error when discord is not running
 - 1.0: Base add-on

### Contributing/Issues
Please post issues on github and not on Anki's site.

Feel free to contact me if you have questions or wish to contribute.
