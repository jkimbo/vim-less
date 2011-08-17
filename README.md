# VIM-LESS #

This vim bundle adds syntax highlighting for the dynamic stylesheet language [LESS](http://lesscss.org).

This bundle is compatible with [vim-css-color](https://github.com/skammer/vim-css-color).

# Includes css indenting file from [Nikolai Weibull](https://gist.github.com/762326/bcbd35239db7f26447f1c2323037d20a5219471d)

## Installing and Using ##

- Install [pathogen](http://www.vim.org/scripts/script.php?script_id=2332) into `~/.vim/autoload/` and add the
   following line to your `~/.vimrc`:

        call pathogen#runtime_append_all_bundles()

     Be aware that it must be added before any `filetype plugin indent on`
     lines according to the install page.

- Make a clone of the `vim-less` repository:

        $ mkdir -p ~/.vim/bundle
        $ cd ~/.vim/bundle
        $ git clone https://github.com/groenewege/vim-less

- OR use git submodules:

        $ git submodule add https://github.com/groenewege/vim-less.git bundle/vim-less
        $ git submodule init

That's it. Pathogen should handle the rest. Opening a file with a `.less`
extension will load everything.

## Credits ##

Inspiration from [vim-haml](https://github.com/tpope/vim-haml), 
[scss-syntax.vim](https://github.com/cakebaker/scss-syntax.vim) and
[vim-less](https://github.com/lunaru/vim-less)
