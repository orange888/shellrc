shellrc - jhol's shell configuration
====================================

Comitting shell config files to a git repository, makes it easy for me to share
my shell preferences between devices.

Installation
------------

On Ubuntu/Debian family:

```
 $ sudo apt install tmux vim zsh
```

### vim

1. Install plug.vim (vim package manager):
```
 $ curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

2. Install vim plugins: run vim, and press `:PlugInstall` then `:bd`.
