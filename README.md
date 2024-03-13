![nvim screenshot](./images/nvim.png)

# Puffcatz's dotfiles

**Warning**:

- Blindly use my settings unless you know what configurations are inside. Any modifications will lead to your own risk.
- This setup is only for coding Golang and Reactjs. If you want to add any language, make sure to check document from [tree-sitter](https://tree-sitter.github.io/tree-sitter/) and [LSP](https://neovim.io/doc/user/lsp.html)

## Contents

- **Neovim** config
- **Tmux** config

## Setup Neovim

### Requirements

- [Neovim](https://neovim.io/) >= **0.9.0** (needs to be built with **LuaJIT**)
- [Tmux](https://github.com/tmux/tmux/wiki)
- Git >= **2.19.0** (for partial clones support)
- [LazyVim](https://www.lazyvim.org/)
- [Nerd Font](https://www.nerdfonts.com/)(v3.0 or greater) **(Need to display some icons on Terminal)**
- [lazygit](https://github.com/jesseduffield/lazygit) **(Optional)**
- **C** compiler for `nvim-treesitter`. See [here](https://github.com/nvim-treesitter/nvim-treesitter#requirements)
- for [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) **_(optional)_**
  - **live grep**: [ripgrep](https://github.com/BurntSushi/ripgrep)
  - **find files**: [fd](https://github.com/sharkdp/fd)
- Terminal: Optional but these are my suggestion Terminals that support true color and *undercurl*:
  - [kitty](https://github.com/kovidgoyal/kitty) **_(Linux & MacOS)_**
  - [wezterm](https://github.com/wez/wezterm) **_(Linux, MacOS & Windows)_**
  - [alacritty](https://github.com/alacritty/alacritty) **_(Linux, MacOS & Windows)_**
  - [iterm2](https://iterm2.com/) **_(MacOS)_**

## Fish Shell setup (macOS & Linux)

- [Fish shell](https://fishshell.com/)
- [Fisher](https://github.com/jorgebucaran/fisher) - Plugin manager
- [Tide](https://github.com/IlanCosman/tide) - Shell theme. Use version 6: `fisher install ilancosman/tide@v6`
- [Nerd fonts](https://github.com/ryanoasis/nerd-fonts) - Powerline-patched fonts. I am using Hack.
- [z for fish](https://github.com/jethrokuan/z) - Directory jumping
- [Eza](https://github.com/eza-community/eza) - `ls` replacement
- [ghq](https://github.com/x-motemen/ghq) - Local Git repository organizer
- [fzf](https://github.com/PatrickF1/fzf.fish) - Interactive filtering
