This repository contains various dotfiles required for setting up unix
utilities.

## Setting up Tmux
```bash
brew install tmux
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
# Contains default tmux configuration.
ln -s <REPO_DIR>/.tmux.conf ~/.tmux.conf
```

## SSH
This step is needed to make SSH Agent forwarding work with tmux.
```bash
mkdir -p ~/.ssh
ln -s <REPO_DIR>/.ssh/rc ~/.ssh/rc
```

