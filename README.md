This repository contains various dotfiles required for setting up unix
utilities.

## Setting up Tmux
```bash
brew install tmux
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
# Contains default tmux configuration.
ln -s $HOME/dotfiles/.tmux.conf ~/.tmux.conf
```
Start a tmux session and Hit prefix (ctrl + b) and I (capital I) to install the
plugins from tmux.conf file. Restart the tmux session to start using all the
plugin functionaality.

## SSH
This step is needed to make SSH Agent forwarding work with tmux.
```bash
mkdir -p ~/.ssh
ln -s $HOME/dotfiles/.ssh/rc ~/.ssh/rc
```

