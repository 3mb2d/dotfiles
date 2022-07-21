# dotfiles

## To clone this repository:

```bash
git clone --recurse-submodules git@github.com:3mb2d/dotfiles.git
```

## Tilix
1. Copy themes from `./tilix/src` to `~/.config/tilix/schemes` (first create directory if it doesn't not exist)
2. Go to Preferences and select your Tilix profile
3. Select Colors tab
4. Select Your favourite theme from dropdown (_Mocha_)

## VSCode

1. Clone this repository into the extentions folder of VSCode:
`~/.vscode/extensions`
2. Open the app
3. type: `SUPER+K SUPER+T`
4. Select the catppuccin theme

## Oh My Posh

1. [Follow Here](https://ohmyposh.dev/docs/installation/linux)
2. cp [config](.OMP/clean-detailed.omp.json)
3. copy contents of [.bash_aliases](.bash_aliases) related to homebrew and OMP (OMP command should be updated with path to config file)

## GTK
1. Install Gnome-Tweaks
2. Shell theme uses compressed install from [gtk](https://github.com/catppuccin/wallpapers/) and legacy applications the uncompressed version
