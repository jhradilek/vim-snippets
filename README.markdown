# Snippets for Vim

## Description

The **vim-snippets** repository provides a collection of snippets for **Vim**, namely for the [UltiSnips](https://github.com/SirVer/ultisnips) (recommended) and [snipMate](https://github.com/msanders/snipmate.vim) plug-ins.

For **UltiSnips**, the following snippets are available:

* **docbk.snippets** — Snippets for the DocBook XML 4.5 language. [Read more…](UltiSnips/docbk.markdown)
* **mallard.snippets** — Snippets for the Mallard XML language. [Read more…](UltiSnips/mallard.markdown)
* **rng.snippets** — Snippets for the RELAX NG schema language for XML. [Read more…](UltiSnips/rng.markdown)

For **snipMate**, the following snippets are included:

* **docbk.snippets** — Snippets for the DocBook XML language. [Read more…](snippets/docbk.markdown)
* **mallard.snippets** — Snippets for the Mallard XML language. [Read more…](snippets/mallard.markdown)
* **rng.snippets** — Snippets for the RELAX NG schema language for XML. [Read more…](snippets/rng.markdown)

## Installation

### Installing the snippets in Vim 8 and newer (recommended)

To install all available snippets by using the native package manager introduced with Vim 8, clone this repository in your **~/.vim/pack/\*/start/** directory. If this directory does not exist, create it by typing the following at a shell prompt:

		install -d ~/.vim/pack/my-plugins/start/

### Installing the snippets using Vundle

To install all available snippets by using the [Vundle](https://github.com/gmarik/vundle) plug-in manager, add the following line to your **~/.vimrc**:

    Plugin 'jhradilek/vim-snippets'

Then run the following command in Vim:

    :PluginInstall

### Installing the snippets using Pathogen

[Pathogen](https://github.com/tpope/vim-pathogen) looks for files in the **~/.vim/bundle/** directory. To make sure that this directory exists, type the following at a shell prompt:

    install -d ~/.vim/bundle/

To install all available snippets, change to the **~/.vim/bundle/** directory and clone this repository in it.

## See also

* [vim-docbk](https://github.com/jhradilek/vim-docbk) — A syntax file, a filetype plug-in, and omni completion for DocBook 4.5 and 5.0.
* [vim-mallard](https://github.com/jhradilek/vim-mallard) — A syntax file, a filetype plug-in, and omni completion for Mallard 1.0.
* [vim-rng](https://github.com/jhradilek/vim-rng) — A syntax file, a filetype plug-in, and omni completion for RELAX NG 1.0.
* [atom-docbook-snippets](https://github.com/pbokoc/atom-docbook-snippets) — A collection of DocBook snippets for **Atom**.
* [emacs-docbook-snippets](https://github.com/jhradilek/emacs-docbook-snippets) — A collection of DocBook snippets for **Emacs**.
* [geany-snippets](https://github.com/jhradilek/geany-snippets) — A collection of DocBook and Mallard snippets for **Geany**.
* [gedit-snippets](https://github.com/jhradilek/gedit-snippets) — A collection of DocBook and Mallard snippets for **Gedit**.

## Copyright

Copyright © 2010–2019 Jaromir Hradilek

This program is free software; see the source for copying conditions. It is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
