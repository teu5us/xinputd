# xinputd &ndash; run scripts when xinput detects your mouse/keyboard

> `xinputd` polls `xinput list` output and runs scripts named as listed devices.

Scripts are placed in `$HOME/.config/xinputd/` and called as devices in `xinput list` (e.g. `"$HOME/.config/xinputd/MX Ergo Mouse"`).

Scripts don't require a shebang as they are run line by line.

There is a 5-second delay between polls.
