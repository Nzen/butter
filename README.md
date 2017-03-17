# butter

A color scheme for Terminal.app and Vim:

![](screenshot.png)

## Installation

1. Download Butter.terminal and run it

2. Copy butter.vim to ~/.vim/colors/butter.vim

3. Add the following lines to ~/.vimrc:

```
syntax on
set t_Co=16
colorscheme butter
```

4. For Python users, we want multiline strings to be highlighted as comments
   rather than strings, because the light background tint on strings looks
   ugly on docstrings. Copy python.vim to ~/.vim/syntax.
