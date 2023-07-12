# Mellow

A soothing dark color scheme for neovim.

## Preview

### Terminal (kitty)
<img width="1673" alt="Screenshot of mellow theme in kitty" src="https://user-images.githubusercontent.com/1040966/196249241-173a1636-b74f-4767-b27f-2b3ed02cea26.png">

## Palette

![Background and foreground](https://user-images.githubusercontent.com/1040966/197761645-8864f33c-a287-4bec-b8fa-2f6c3033f380.png)
![Grays](https://user-images.githubusercontent.com/1040966/197760220-e8c71e34-e421-474b-819d-4acd12e126de.png)
![Normal colors](https://user-images.githubusercontent.com/1040966/197760225-9a3e3ff0-7ee0-426f-9646-c4b5e3dc0acc.png)
![Bright colors](https://user-images.githubusercontent.com/1040966/197760222-f2f43028-b3b8-4480-be79-5ec95a330db7.png)

## Features

- Supports the latest neovim `0.8`.
- Terminal colors inside neovim.

### Differences from the original mellow.nvim
- DiagnosticErrors are red and DiagnosticWarns are yellow
- DiagnosticVirtualTexts are the same color as Comment but is bold and undercurl
- Less bright nvim-ts-rainbow's, move Red to the end of the color set
- Somewhat distinct colors in nvim-cmp menus
- Clearer Visual selections
- Hidden EndOfBuffer characters
- Clearer Telescope matching highlights
- WinBarError for my own config
- Bold StatusLine

### Plugin Support

- [TreeSitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [LSP Diagnostics](https://neovim.io/doc/user/lsp.html)
- [Lualine](https://github.com/nvim-lualine/lualine.nvim)
- [Git Signs](https://github.com/lewis6991/gitsigns.nvim)
- [Telescope](https://github.com/nvim-telescope/telescope.nvim)
- [Indent Blankline](https://github.com/lukas-reineke/indent-blankline.nvim)
- [nvim-cmp](https://github.com/hrsh7th/nvim-cmp)

## Requirements

- Neovim >= 0.8.0

## Installation

Head to the original at [kvrohit/mellow.nvim](https://github.com/kvrohit/mellow.nvim) instead, for this has my personal customizations and might be behind in updates

## Credits

- [kvrohit/mellow.nvim](https://github.com/kvrohit/mellow.nvim)
