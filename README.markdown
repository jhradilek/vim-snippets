# Snippets for Vim

## Description

The **vim-snippets** repository provides a collection of code snippets for **Vim**. In particular, it contains snippets for the following two frequently used plug-ins:

* [UltiSnips](https://github.com/SirVer/ultisnips) by [Holger Rapp](https://github.com/SirVer) (recommended)
* [snipMate](https://github.com/msanders/snipmate.vim) by [Michael Sanders](https://github.com/msanders), [Rok Garbas](https://github.com/garbas), and [Marc Weber](https://github.com/MarcWeber)

The following snippets are available for the **UltiSnips** plug-in in the **UltiSnips** directory:

* **docbk.snippets** — Snippets for the DocBook XML language. [Read more…](UltiSnips/docbk.markdown)
* **mallard.snippets** — Snippets for the Mallard XML language. [Read more…](UltiSnips/mallard.markdown)
* **rng.snippets** — Snippets for the RELAX NG schema language for XML. [Read more…](UltiSnips/rng.markdown)

The following snippets are available for the **snipMate** plug-in in the **snippets** directories:

* **docbk.snippets** — Snippets for the DocBook XML language. [Read more…](snippets/docbk.markdown)
* **mallard.snippets** — Snippets for the Mallard XML language. [Read more…](snippets/mallard.markdown)
* **rng.snippets** — Snippets for the RELAX NG schema language for XML. [Read more…](snippets/rng.markdown)

## Installation

### Installing the Snippets Using Vundle

To install all available snippets by using the [Vundle](https://github.com/gmarik/vundle) plug-in manager, add the following line to your **~/.vimrc**:

    Bundle 'jhradilek/vim-snippets'

Then run the following command in Vim:

    :BundleInstall

### Installing the Snippets Using Pathogen

[Pathogen](https://github.com/tpope/vim-pathogen) looks for files in the **~/.vim/bundle/** directory. To make sure that this directory exists, type the following at a shell prompt:

    install -d ~/.vim/bundle/

To install all available snippets, change to the **~/.vim/bundle/** directory and clone this repository in it.

### Installing the Snippets Manually

#### Installing Snippets for All Plug-ins

Snippets are locally stored in the **~/.vim/** directory. To make sure that this directory exists, type the following at a shell prompt:

    mkdir ~/.vim/

To manually install all available snippets for all supported plug-ins, change to the directory with your local copy of this repository and run the following command:

    cp -R * ~/.vim

#### Installing Snippets for the UltiSnips Plug-in

By default, the snippets for the **UltiSnips** plug-in are stored in the **~/.vim/UltiSnips/** directory. To make sure that this directory exists, type the following at a shell prompt:

    install -d ~/.vim/UltiSnips/

To install any of the available snippets, change into the directory with your local copy of this repository and run the following command:

    cp UltiSnips/<filetype>.snippets ~/.vim/UltiSnips/

This copies the selected file to the **~/.vim/UltiSnips/** directory. For example, to install the snippets for the DocBook XML language, type:

    cp UltiSnips/docbk.snippets ~/.vim/UltiSnips/

The snippets are loaded immediately.

#### Installing Snippets for the snipMate Plug-in

By default, the snippets for the **snipMate** plug-in are stored in the **~/.vim/snippets/** directory. To make sure that this directory exists, type the following at a shell prompt:

    install -d ~/.vim/snippets/

To install any of the available snippets, change into the directory with your local copy of this repository and run the following command:

    cp snippets/<filetype>.snippets ~/.vim/snippets/

This copies the selected file to the **~/.vim/snippets/** directory. For example, to install the snippets for the DocBook XML language, type:

    cp snippets/docbk.snippets ~/.vim/snippets/

The snippets are automatically loaded the next time you open a DocBook file.

## See Also

* [vim-docbk](https://github.com/jhradilek/vim-docbk) — A syntax file, a filetype plug-in, and omni completion for DocBook 4.5 and 5.0.
* [vim-mallard](https://github.com/jhradilek/vim-mallard) — A syntax file, a filetype plug-in, and omni completion for Mallard 1.0.
* [vim-rng](https://github.com/jhradilek/vim-rng) — A syntax file, a filetype plug-in, and omni completion for RELAX NG 1.0.

## Copyright

Copyright © 2010–2013 Jaromir Hradilek

This program is free software; see the source for copying conditions. It is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
