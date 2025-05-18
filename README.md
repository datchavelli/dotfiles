```
████████╗███████╗ █████╗ ██████╗
╚══██╔══╝╚══███╔╝██╔══██╗██╔══██╗
   ██║     ███╔╝ ███████║██████╔╝
   ██║    ███╔╝  ██╔══██║██╔══██╗
   ██║   ███████╗██║  ██║██║  ██║
   ╚═╝   ╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝
            [@tz_]
```

# dotfiles

This repository contains my personal dotfiles and configuration files for various tools and environments.

## Contents

- `.config/` — Configuration files for various applications (terminal, weztermn, neovim etc.)
- `.bashrc` — Bash shell customizations
- Other shell and app config files

## Technologies Used

- **Lua** — For configuring tools like wezterm, neovim
- **Shell** — Bash/Zsh configuration and script automation

## Installation

To use these dotfiles:

```bash
git clone https://github.com/datchavelli/dotfiles.git ~/dotfiles
cd ~/dotfiles
# Manually copy what you need or symlink them:
cp -r .config/* ~/.config/
cp .bashrc ~/
```
