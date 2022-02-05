## Overview

This project contains my zsh and vim dotfiles

Clone this project then execute the following to use the configuration files.

```bash 
git clone git@github.com:mcornstubble/dotfiles ~/
```

### vim
```bash
# Clean up old unnecessary files or symlinks
rm -f ~/.vimrc ~/.gvimrc ~/.vimrc.bundles; rm -rf ~/.vim
```

```bash 
# vim
mv ~/dotfiles/vim ~/.vim
```

### zsh
```bash
mv ~/dotfiles/zshrc ~/.zshrc
```
