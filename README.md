# Dotfiles

Here are my personnal dotfiles, and how to install them.

Run :

```bash
sudo apt install i3
```

Restart your computer and select i3 before login.

Create a config file, and choose Win as the Mod key.

Copy `.config/i3/*` in `/home/.config/i3`.

Copy `.config/rofi/`.

Copy `.bashrc`.

Copy `.fonts/`

Copy `scripts/`

Copy `.config/gtk-3.0/settings.ini`

Copy `tmux.conf`

Install [this](https://addons.mozilla.org/en-US/firefox/addon/arc-darker/?src=search) theme on Firefox.

```bash
chmod +x scripts/lock.sh
sudo apt install zsh tmux rofi scrot curl lxappearance arc-theme compton i3blocks xbacklight redshift feh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
sudo add-apt-repository -u ppa:snwh/ppa
sudo apt-get install moka-icon-theme faba-icon-theme faba-mono-icons
```

Update the icon theme in `lxappearance`.

Press `Win+e`to exit.

Go back in a new session and open a terminal.

Do `Ctrl+b`and `Ctrl+:`

Enter `source-file /home/salim/.tmux.conf`

Install `Spotify` from package manager.
