# nerd-nvim
> this nvim configure for my personal use

it might be useful for you, if you want to start configuring your perosnal nvim set.

## Installtion Guide

```
sudo snap install nvim --classic
```
here, I'm installing nvim via snap store


```
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```
installing nvim plugin manager.

that's it what we need for installtion for our minimal nvim

## Configuring nvim 

```
git clone https://github.com/meanii/nerd-nvim; cd nerd-nvim; mkdir -p ~/.config/nvim/; cp init.vim ~/.config/nvim/init.vim

```
so here, we have initiated our init.vim config file, so next we need it install all plugins

```
nvim ~/.config/nvim/init.vim
```

get into command model then `:PlugInstall`, this gonna install your all required plugins.
