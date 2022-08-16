# ARCH Linux configuration files
Dotfiles are configuration files for various programs, and they help those programs manage their functionality.

## Setup
- OS: [Arch linux](https://archlinux.org/)
- WM: [bspwm](https://github.com/baskerville/bspwm)
- Terminal: [Alacritty](https://github.com/alacritty/alacritty)
- Shell: [zsh](https://www.zsh.org/)
- Editor: [neovim](https://github.com/neovim/neovim)
- Compositor: [picom](https://github.com/Arian8j2/picom-jonaburg-fix.git)
- Application Launcher: [rofi](https://github.com/davatorium/rofi)
- Bar: [Polybar](https://github.com/polybar/polybar)
- wallpaper setter: [feh](https://feh.finalrewind.org/)
- Notification daemon: [dunst](https://dunst-project.org/)
- media player: [mpv](https://mpv.io/)

## Installation
Clone the repository into your `$HOME` directory
	```
		git clone https://github.com/chitranshk1301/dotfiles
	```

Run `stow` to symlink everything or just select what you want
	```cd dotstow/base/ && stow */  -t```
