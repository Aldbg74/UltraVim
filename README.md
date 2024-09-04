# UltraVim
Vim but for bg at Epitech


<h1>Step One</h1>
Install Vim-Plug : https://github.com/junegunn/vim-plug <br>
Install Tmux : https://github.com/tmux/tmux (not related to vim but kinda helpful when in tty) <br>

<h1>Step Two</h1>
Create a .vimrc files in your Home. If there is allready a .vimrc files please save it in a safe space. <br>

<h1>Step Three</h1>
Open your .vimrc files with any editor and put inside the code below :

```
set number
syntax on

call plug#begin()

" List your plugins here
Plug 'tpope/vim-sensible'
Plug 'deadbaed/vim-epitech'
Plug 'preservim/nerdtree'
Plug 'flazz/vim-colorschemes'
Plug 'itchyny/lightline.vim'
Plug 'dense-analysis/ale'

call plug#end()
```

Ofc Save your files before exiting the file.

<h1>Step Four</h1>
Open vim and use <br>

```
:PlugInstall
```

<h1>Step Five</h1>
Wait till all package install <br>

<h1>Step Six</h1>
Enjoy<br>
