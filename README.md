# dotfiles

## How to install

Clone repo:
```sh
git clone --bare https://github.com/mykykh/dotfiles.git $HOME/.dotfiles
```

Checkout files:
```sh
git --git-dir=$HOME/.dotfiles --work-tree=$HOME checkout
```

## How to use

Add new files:
```sh
dot add -f new_file
```
