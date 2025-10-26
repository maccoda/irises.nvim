# irises.nvim

A theme inspired by irises, the plant and Van Gogh's painting.

Supports tree sitter and semantic highlighting.

[![Screenshot](https://i.postimg.cc/0NKTWrxp/Screenshot-From-2025-06-07-20-26-49.png)](https://postimg.cc/CZYrdhR1)

## Installing

### Lazy

```lua
{
  "maccoda/irises.nvim",
  lazy = false,
  priority = 1000,
  config = function()
    vim.cmd.colorscheme 'irises'
  end,
}
```

## Supported plugins

- [Blink](https://github.com/Saghen/blink.lua)
- [Gitsigns](https://github.com/lewis6991/gitsigns.nvim)
- [Lualine](https://github.com/nvim-lualine/lualine.nvim)
- [Snacks.nvim](https://github.com/folke/snacks.nvim)
- [WhichKey](https://github.com/folke/which-key.nvim)

## Acknowledgements

- [Tokyo night](https://github.com/folke/tokyonight.nvim/tree/main)
- [Gruvbox](https://github.com/ellisonleao/gruvbox.nvim/tree/main)
