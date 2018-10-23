# Optimum ViM Configuration

My own Optimum ViM Configuration

Install the plugin manager
1. git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim
2. Add the following configs to .vimrc

set nocompatible              " required
filetype off                  " required

" set the runtime path to include Vundle and initialize
set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()

" alternatively, pass a path where Vundle should install plugins
"call vundle#begin('~/some/path/here')

" let Vundle manage Vundle, required
Plugin 'gmarik/Vundle.vim'

" add all your plugins here (note older versions of Vundle
" used Bundle instead of Plugin)

" ...

" All of your Plugins must be added before the following line
call vundle#end()            " required
filetype plugin indent on    " required


https://github.com/Valloric/YouCompleteMe

https://vi.stackexchange.com/questions/7470/how-to-install-youcompleteme-with-clang-completer-offline
