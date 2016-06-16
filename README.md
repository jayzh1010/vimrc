# vimrc
my vimrc, based on the amix/vimrc(git@github.com:amix/vimrc.git)


1. clone this repo

    /usr/bin/env git clone git://github.com/jayzh1010/vimrc.git $HOME/.vim
    ln -s $HOME/.vim/vimrc $HOME/.vimrc
    mkdir $HOME/.config
    ln -s $HOME/.vim $HOME/.config/nvim
    ln -s $HOME/.vim/vimrc $HOME/.config/nvim/init.vim

2. set up vundle

    git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim

3. set up plugin

    vim 
    :PluginInstall
