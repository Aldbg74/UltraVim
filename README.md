<h1>ULTRAVIM</h1>
Vim but for the giga chad at Epitech

![Gigachad](https://datepsychology.com/wp-content/uploads/2022/09/gigachad.jpg)


<h2>Step One</h2>
Install Vim-Plug : https://github.com/junegunn/vim-plug <br>
Install Tmux : https://github.com/tmux/tmux (not related to vim but kinda helpful when in tty) <br>
<br>

> [!IMPORTANT]
> The complete and correct installation of vim-plug is required for the rest
> Try with :PlugStatus when in vim for check if all is good
> If it's works good lets go to step 2
> If not return to step one

<h2>Step Two</h2>
Create a .vimrc files in your Home. 
<br>

> [!WARNING]
> If there is allready a .vimrc file please save it in a safe space. <br>

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

> [!NOTE]
> Ofc Save your files before exiting.

<h2>Step Four</h2>
Open vim and use <br>


```
:PlugStatus
```
And after <br>

```
:PlugInstall
```

<h2>Step Five</h2>
Wait till all package install <br>

<h2>Step Six</h2>
Enjoy<br>

> [!IMPORTANT]
> All commands are on the other .md files for a better readability.

<h3>Credits</h3>

[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/featured/featured-powered-by-electricity.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/powered-by-coffee.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/powered-by-watergate.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/contains-tasty-spaghetti-code.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/0-percent-optimized.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/works-on-my-machine.svg)](https://forthebadge.com)







