# vim-monokai

Monokai color scheme for Vim converted with [coloration](http://coloration.sickill.net) from Textmate theme with the same name.


# Screenshots

**Python Highlighting**

![Python Highlighting](https://github.com/hendiko/vim-monokai/blob/master/screenshot/py_screenshot.png "py_screenshot.png")

**C Highlighting**

![C Highlighting](https://github.com/hendiko/vim-monokai/blob/master/screenshot/c_screenshot.png "c_screenshot.png")

**Java Highlighting**

![Java Highlighting](https://github.com/hendiko/vim-monokai/blob/master/screenshot/java_screenshot.png "java_screenshot.png")


# Installation

## 1. Use [Vundle](https://github.com/gmarik/Vundle.vim "Vundle.vim")

Put this line in your `~/.vimrc`:

    call vundle#begin()
    Plugin 'hendiko/vim-monokai' 
    call vundle#end()

Then run command `vi +PluginInstall`, and add the two lines below to your `~/.vimrc` in any line after `call vundle#end()`

    syntax enable
    colorscheme monokai

## 2. Manual 

Put `monokai.vim` file in your `~/.vim/colors/` directory and add the following line to your `~/.vimrc`:

    syntax enable
    colorscheme monokai


# Changes

I made some slight adjustments to suffice myself.

    LineNr ctermbg=0 
    Pmenu ctermbg=174
    PmenuSel ctermbg=160 
    Normal ctermfg=254 ctermbg=0
    NonText ctermbg=0

It becomes more clear contrast with dark black background.
