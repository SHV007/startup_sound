# A script for enabling sound on startup on X server (mine will play the intel logo sound)

first download a favorite sound and place it in `/usr/share/sounds/`
you'll have to download "mplayer" to make it work
after it place * *startup_sound* * script in `/usr/bin/` and make it executable
and then place the .service in `/etc/systemd/system/` and enable the service.

**won't work with other shell than bash (tried to make it work with zsh and didn't get any result. but will make my best to make it work)**

that's it :)
