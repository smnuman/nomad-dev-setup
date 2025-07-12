# NOMAD Dev Setup

A minimal, modular development environment built for terminal-first workflows and portable productivity.

This setup is designed for modern developers who:
- Prefer Zsh, Neovim, and Git for everyday work
- Work across Python (light), Node.js, Rust, and Ruby on Rails
- Use `tmux` for persistent, split-pane sessions
- Want everything version-controlled and reproducible

## ✨ Features

- **Modular Lua-based Neovim config**
  - Uses `lazy.nvim` for efficient plugin management
  - Includes `nvim-tree` with Nerd Font support
  - No bloat, just productivity

- **Minimal `tmux.conf`**
  - Smart splits
  - Vim navigation integration
  - Optional session persistence with `tmux-resurrect`

- **Clean Brewfile**
  - Installs only what you need
  - Languages: Python, Node.js, Ruby, Rust
  - Tools: `fzf`, `zoxide`, `ripgrep`, `fd`, `bat`, `exa`

- **Portable Design**
  - All configs live under `~/.config`
  - Easy to clone, update, and sync across machines

## 📦 Includes
```
NOMAD-Dev-Setup/
├── Brewfile
├── .tmux.conf
├── README.md
└── nvim/
    ├── init.lua
    └── lua/
        └── user/
            ├── options.lua
            ├── keymaps.lua
            ├── colorscheme.lua
            ├── plugins.lua
            └── nvim-tree.lua
```
