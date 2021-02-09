daqo's dotfiles
---

To install run `curl -Lks http://bit.do/daqo-dotfiles | /bin/zsh`. Be cautious, this will replace your existing dotfiles with the ones from this repo.

To have all vim plugins installed, you need to install vim-plug first:

1. Install vim-plug
```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
2. Open vim and type `:PlugInstall`

The instructions here are based on Atlassian [guide](https://www.atlassian.com/git/tutorials/dotfiles).
