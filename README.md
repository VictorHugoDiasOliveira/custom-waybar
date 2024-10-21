# custom-waybar

move config.jsonc
```zsh
mv config.jsonc ~/.config/waybar
```

then just kill waybar and start exec it again
```zsh
pkill waybar && hyprctl dispatch exec waybar
```
