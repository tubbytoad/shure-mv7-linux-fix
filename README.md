# shure-mv7-linux-fix
Fix for Shure MV7 on Linux

Set the `default-sample-rate = 48000` in daemon.conf (in `/etc/pulse/daemon.conf` or `~/.config/pulse/daemon.conf`).

Haven't tested but you may need `shure-mv7.conf` in `/usr/share/alsa-card-profile/mixer/profile-sets/` for monitor support

Reboot.

You may have to unplug and replug your usb once you are logged in again.

Use `pavucontrol` to set the MV7 to Analog Stereo Output + Mono Input.
