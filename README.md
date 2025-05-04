# SwayNC-Wallbash

## Installation:

Install the package `swaync`

Edit `~/.config/hyde/config.toml`

Add this to the bottom of the file:
```
[hyprland-start]
notifications = "swaync"
```

Place "swaync.dcol" to `~/.config/hyde/wallbash/always/`

Place "swaync.sh" to `~/.config/hyde/wallbash/scripts/`

And place "config.json" to `~/.config/swaync/config.json`

Then, run:

`chmod +x ~/.config/hyde/wallbash/scripts`

Finally, run:

`color.set.sh --single ~/.config/hyde/wallbash/always/swaync.dcol`

Then, simply log out and back in.
