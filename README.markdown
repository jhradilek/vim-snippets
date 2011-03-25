Vim Snippets
============


System Requirements
-------------------

A working installation of Felix Ingram's SnippetsEmu plug-in is required in order to use these snippets. Refer to the [plug-in homepage](http://www.vim.org/scripts/script.php?script_id=1318) for download options and further instructions how to install it.


Installing the Snippets on Linux
--------------------------------

The snippets for various file types are stored in the `~/.vim/after/ftplugin/` directory. To ensure that this directory exists, type the following commands at a shell prompt:

    mkdir ~/.vim
    mkdir ~/.vim/after
    mkdir ~/.vim/after/ftplugin

To install snippets for a particular file type, copy the relevant file to the above directory by using the following command:

    cp <filetype>_snippets.vim ~/.vim/after/ftplugin/

The snippets are loaded automatically the next time you open a DocBook file.


Copyright
---------

Copyright © 2010, 2011 Jaromir Hradilek

This program is free software; see the source for copying conditions. It is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
