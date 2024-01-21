# Onehalf
This is a slightly modified version of the [Onehalf theme by sonph](https://github.com/sonph/onehalf).

It works with Vim and Neovim.

# Installation & Usage
![screenshot: vim](screenshots/vim.png)
NeoVim + Tmux with true colors on iTerm2.

## Installation with package manager

### Lazy
```lua
{
  "MarcoKorinth/onehalf.nvim",
  lazy = false
}

-- somewhere in your config:
vim.cmd("colorscheme onehalf")
```

### Packer
```lua
use "MarcoKorinth/onehalf.nvim"

-- somewhere in your config:
vim.cmd("colorscheme onehalf")
```

### Vim-Plug
```vim
Plug "MarcoKorinth/onehalf.nvim"

" somewhere in your config:
colorscheme onehalf
```
