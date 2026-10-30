# alacritty

Minimalny config **Alacritty**: czarne tło, jasnoszary tekst, przezroczystość 0.95. Na Hyprlandzie z rozmyciem wygląda to jak szkło. **Shift+Enter** wysyła `Esc`+`Enter`, czyli nową linię w TUI typu Claude Code.

Czcionka jest systemowa (`monospace`). Shell bierze się z `$SHELL`, u mnie to fish.

> Część zestawu **[linux-tools](https://github.com/K-u-r-c/linux-tools)**. Pasuje do [tmux](https://github.com/K-u-r-c/tmux), [nvim](https://github.com/K-u-r-c/nvim), [waybar](https://github.com/K-u-r-c/waybar) i [command-center](https://github.com/K-u-r-c/command-center), które otwierają w nim programy terminalowe.

## Instalacja

```bash
sudo pacman -S --needed alacritty
[ -d ~/.config/alacritty ] && mv ~/.config/alacritty ~/.config/alacritty.bak
git clone https://github.com/K-u-r-c/alacritty ~/.config/alacritty
```

Aktualizacja: `git -C ~/.config/alacritty pull` (Alacritty sam przeładowuje config).
