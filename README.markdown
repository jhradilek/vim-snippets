# Vim Snippets

## Description

The **vim-snippets** repository provides a collection of code snippets for **Vim**. In particular, it provides snippets for two plug-ins: [snipMate](http://www.vim.org/scripts/script.php?script_id=2540) by Michael Sanders, and [snippetsEmu](http://www.vim.org/scripts/script.php?script_id=1318) by Felix Ingram.

For the **snipMate** plug-in, the following snippets are included in the **snipMate** directory:

* **docbk.snippets** — Snippets for the DocBook XML language according to the [DocBook: The Definitive Guide, version 2.0.17](http://www.docbook.org/tdg/).

* **mallard.snippets** — Snippets for the Mallard XML language according to [Mallard 1.0 DRAFT (as of 2013-02-11)](http://projectmallard.org/1.0/index.html). See also my [vim-syntax](https://github.com/jhradilek/vim-syntax) repository for a syntax file for this language.

For the **snippetsEmu** plug-in, the following snippets are available in the **snippetsEmu** directory:

* **docbk_snippets.vim** — Snippets for the DocBook XML language according to the [DocBook: The Definitive Guide, version 2.0.17](http://www.docbook.org/tdg/).

## Installation

### Installing Snippets for the snipMate Plug-in

To install snippets for the **snipMate** plug-in, change into the directory with your local copy of this repository and run the following command:

    cp snipMate/<filetype>.snippets ~/.vim/snippets/

For example, to install the snippets for the DocBook XML language, type:

    cp snipMate/docbk.snippets ~/.vim/snippets/

This copies the selected file to the **~/.vim/snippets/** directory. Note that the directory must exist prior to running this command; to create it, type the following at a shell prompt:

    install -d ~/.vim/snippets/

The snippets are automatically loaded the next time you open a DocBook file.

### Installing Snippets for the snippetsEmu Plug-in

To install snippets for the **snippetsEmu** plug-in, change into the directory with your local copy of this repository and run the following command:

    cp snippetsEmu/<filetype>_snippets.vim ~/.vim/after/ftplugin/

For example, to install the snippets for the DocBook XML language, type:

    cp snippetsEmu/docbk_snippets.vim ~/.vim/after/ftplugin/

This copies the selected file to the **~/.vim/after/ftplugin/** directory. Note that the directory must exist prior to running this command; to create it, type the following at a shell prompt:

    install -d ~/.vim/after/ftplugin/

The snippets are automatically loaded the next time you open a DocBook file.

## Uninstallation

### Uninstalling Snippets for the snipMate Plug-in

To uninstall snippets for the **snipMate** plug-in, run the following command:

    rm ~/.vim/snippets/<filetype>.snippets

For example, to uninstall the snippets for the DocBook XML language, type:

    rm ~/.vim/snippets/docbk.snippets

### Uninstalling Snippets for the snippetsEmu Plug-in

To uninstall snippets for the **snippetsEmu** plug-in, run the following command:

    rm ~/.vim/after/ftplugin/<filetype>_snippets.vim

For example, to uninstall the snippets for the DocBook XML language, type:

    rm ~/.vim/after/ftplugin/docbk_snippets.vim

## Copyright

Copyright © 2010—2012 Jaromir Hradilek

This program is free software; see the source for copying conditions. It is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
