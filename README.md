# neovim

1. Install Alacritty
```
brew install --cask alacritty
```
2. Install Fonts
```
brew search font- | grep jetbrains
```
3. Configure Alacritty
```
.config/alacritty/alacritty.toml

[env]
TERM = "xterm-256color"

[font]
normal.family = "JetBrainsMono Nerd Font"
size = 20
```
4. Install neovim
```
brew install neovim
```
5. Install NvChad
```
git clone https://github.com/NvChad/starter ~/.config/nvim

:MasonInstallAll
```
