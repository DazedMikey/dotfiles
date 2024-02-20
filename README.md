# Dotfiles

## Setup dotfiles
```
cd ~
git clone git@github.com:DazedMikey/dotfiles.git
```

### Install GNU Stow
##### Arch
```
pacman -S stow
```

## Adding files to dotfiles
```
cd ~/dotfiles
cp ~/.foo ~/dotfiles
mv ~/.foo ~/.foo.bak
stow .
```
