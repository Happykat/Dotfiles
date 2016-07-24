# My dotfiles

## Content

 * neovim configuration : init.vim
 * tmux configuration   : .tmux.conf
 * zsg configuration    : .zshrc


## Depencencies

 * neovim
 * tmux
 * zsh
 * [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
 * [bullet-train for oh-my-zsh](https://github.com/caiogondim/bullet-train-oh-my-zsh-theme)

 There are some screenshots at the end of this README. My terminal is using the Monokai palette for Guake.

## Install

### Clone this repo 

```sh
$ git clone git@github.com:Happykat/Dotfiles.git
```

### Copy the files

```sh
$ cp .tmux.conf ~
```

```sh
$ cp init.vim $XDG_CONFIG_HOME/nvim
```
$XDG_CONFIG_HOME might not be set for you , it default to /home/.config
Also to have persistant undo make sure to create the undodir directory :

```sh
$ mkdir ~/.config/nvim/undodir
```

```sh
$ cp .zshrc ~
```

### Zsh

edit the .zshrc to change the home directory according to yours.

``` "(YOUR_HOME)" becomes your actual home ```


## Influences

My init.vim is LARGELY based on [mhartington's](https://github.com/mhartington)

You will find in his repos , some awesomes dotfiles , neovim themes etc...

Most of the credits for the neovim config goes to him.

## Result

## Terminal
![Alt text](img/terminal.png?raw=true "Title")

## Neovim
![Alt text](img/neovim.png?raw=true "Title")
