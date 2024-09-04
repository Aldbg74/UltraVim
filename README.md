# UltraVim
Vim but for bg at Epitech


<h2>Step One</h2>
Install Vim-Plug : https://github.com/junegunn/vim-plug <br>
Install Tmux : https://github.com/tmux/tmux (not related to vim but kinda helpful when in tty) <br>

<h2>Step Two</h2>
Create a .vimrc files in your Home. If there is allready a .vimrc files please save it in a safe space. <br>

<h2>Step Three</h2>
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

<h2>Step Four</h2>
Open vim and use <br>

```
:PlugInstall
```

<h2>Step Five</h2>
Wait till all package install <br>

<h2>Step Six</h2>
Enjoy<br>
