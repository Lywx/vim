Vim
===

    My vim configuration.

Installation
===

    git clone git://github.com/Lywx/vim.git  ~/.vim

    ln -s ~/.vim/dotfiles/vimrc ~/.vimrc
    ln -s ~/.vim/dotfiles/tmux.conf ~/.tmux.conf
    ln -s ~/.vim/dotfiles/bashrc ~/.bashrc

    ln -s ~/.vim/bin/git_diff_wrapper ~/bin/git_diff_wrapper

    git config --global diff.external git_diff_wrapper
