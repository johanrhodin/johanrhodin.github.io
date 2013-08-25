---
layout: post
title: "Modelica Syntax Highlighting for Vim"
date: 2013-08-25 12:09
comments: true
categories: [Modelica, Vim]
---
Setting up syntax highlighting for Modelica is something I do when I switch computers. So not all that often, but it happens. And everytime there's something I forget to do, so here's something to remind myself.

### Steps to set it up

1. Download/clone [vim-modelica](https://github.com/Twinside/vim-modelica)
2. Create the folder ~/.vim (if you don't already have it)
3. Move the folders /syntax and /ftdetect from /vim-modelica into ~/.vim
4. Add "syntax on" to the file ~/.vimrc (create it if it's not there)
5. (Optional) Add a colorscheme to ~/.vimrc, with "colorscheme [solarized]( 
http://ethanschoonover.com/solarized/vim-colors-solarized)"
6. (Optional) Install a nice font such as inconsolata.

The end result?
![Part of the Planar Mechanics library](../images/syntax_highlighted_modelica.png "Dirk Zimmer's Planar Mechanics library in MacVim")

