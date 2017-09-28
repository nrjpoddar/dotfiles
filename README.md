This repository contains various dotfiles required for setting up unix
utilities.

## TMUX Conf
Contains default tmux configuration.
```bash
ln -s <REPO_DIR>/tmux.conf ~/.tmux.conf
```

## SSH
This step is needed to make SSH Agent forwarding work with tmux.
```bash
mkdir -p ~/.ssh
ln -s <REPO_DIR>.ssh/rc ~/.ssh/rc
```

