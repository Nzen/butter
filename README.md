Butter, a low-contrast color scheme for Terminal.app/Vim, made by
someone who reads code all day.

![](screenshot.png#1)

## Installation

Run this:

```
git clone https://github.com/brhs/butter
cd butter
open Butter.terminal
mkdir -p ~/.vim/colors
cp butter.vim ~/.vim/colors/butter.vim
```

Add the following lines to your vimrc file:

```
syntax on
set t_Co=16
colorscheme butter
```

For Python, we want multiline strings highlighted as comments rather than
strings, because the background tint looks ugly on docstrings:

```
mkdir -p ~/.vim/syntax
cp python.vim ~/.vim/syntax/python.vim
```

## Inspirations

 * [I can't believe it's not butter](http://dotshare.it/dots/672/) for color base
 * Zenburn for general inspiration
 * [Some dude called Irwin/x0r](https://hostr.co/files/lwioNAx/capture.png) for the highlighted strings

