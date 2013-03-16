# Vim Snippets

## Description

The **vim-snippets** repository provides a collection of code snippets for **Vim**. In particular, it contains snippets for the following three frequently used plug-ins:

* [UltiSnips](https://github.com/SirVer/ultisnips) by [Holger Rapp](https://github.com/SirVer),
* [snipMate](https://github.com/msanders/snipmate.vim) by [Michael Sanders](https://github.com/msanders), [Rok Garbas](https://github.com/garbas), and [Marc Weber](https://github.com/MarcWeber), and
* [snippetsEmu](http://www.vim.org/scripts/script.php?script_id=1318) by Felix Ingram.

For the **UltiSnips** and **snipMate** plug-ins, the following snippets are included in their respective directories:

* **docbk.snippets** — Snippets for the DocBook XML language according to [DocBook: The Definitive Guide, version 2.0.17](http://www.docbook.org/tdg/).
* **mallard.snippets** — Snippets for the Mallard XML language according to [Mallard 1.0 DRAFT (as of 2013-02-11)](http://projectmallard.org/1.0/index.html). See also my [vim-syntax](https://github.com/jhradilek/vim-syntax) repository for a syntax file for this language.

For the **snippetsEmu** plug-in, the following legacy snippets are available in the **snippetsEmu** directory, but are no longer actively developed or maintained:

* **docbk_snippets.vim** — Snippets for the DocBook XML language according to the [DocBook: The Definitive Guide, version 2.0.17](http://www.docbook.org/tdg/).

## Installation

### Installing Snippets for the UltiSnips Plug-in

By default, the snippets for the **UltiSnips** plug-in are stored in the **~/.vim/UltiSnips/** directory. To make sure that this directory exists, type the following at a shell prompt:

    install -d ~/.vim/UltiSnips/

To install any of the available snippets, change into the directory with your local copy of this repository and run the following command:

    cp UltiSnips/<filetype>.snippets ~/.vim/UltiSnips/

This copies the selected file to the **~/.vim/UltiSnips/** directory. For example, to install the snippets for the DocBook XML language, type:

    cp UltiSnips/docbk.snippets ~/.vim/UltiSnips/

The snippets are loaded immediately.

### Installing Snippets for the snipMate Plug-in

By default, the snippets for the **snipMate** plug-in are stored in the **~/.vim/snippets/** directory. To make sure that this directory exists, type the following at a shell prompt:

    install -d ~/.vim/snippets/

To install any of the available snippets, change into the directory with your local copy of this repository and run the following command:

    cp snipMate/<filetype>.snippets ~/.vim/snippets/

This copies the selected file to the **~/.vim/snippets/** directory. For example, to install the snippets for the DocBook XML language, type:

    cp snipMate/docbk.snippets ~/.vim/snippets/

The snippets are automatically loaded the next time you open a DocBook file.

### Installing Snippets for the snippetsEmu Plug-in

By default, the snippets for the **snippetsEmu** plug-in are stored in the **~/.vim/after/ftplugin/** directory. To make sure that this directory exists, type the following at a shell prompt:

    install -d ~/.vim/after/ftplugin/

To install any of the available snippets, change into the directory with your local copy of this repository and run the following command:

    cp snippetsEmu/<filetype>_snippets.vim ~/.vim/after/ftplugin/

This copies the selected file to the **~/.vim/after/ftplugin/** directory. For example, to install the snippets for the DocBook XML language, type:

    cp snippetsEmu/docbk_snippets.vim ~/.vim/after/ftplugin/

The snippets are automatically loaded the next time you open a DocBook file.

## Copyright

Copyright © 2010—2013 Jaromir Hradilek

This program is free software; see the source for copying conditions. It is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
