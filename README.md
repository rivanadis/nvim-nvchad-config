
# NvChad Config (Python, Go, JS)

Personal Neovim IDE config based on NvChad (starter).

## Features
- LSP: pyright, gopls, tsserver
- Formatter: black, isort, gofumpt, goimports, prettierd
- Format on save (conform.nvim)

## Notes

> Install tools via :Mason
> - LSP: pyright, gopls, tsserver
> - Formatter: black, isort, gofumpt, goimports, prettierd

## Install

### Windows
**powershell**
```
Remove-Item -Recurse -Force $env:LOCALAPPDATA\nvim -ErrorAction SilentlyContinue
git clone https://github.com/rivanadis/nvim-nvchad-config $env:LOCALAPPDATA\nvim
nvim
```
### LINUX
```BASH/ZSH
rm -rf ~/.config/nvim
git clone https://github.com/rivanadis/nvim-nvchad-config ~/.config/nvim
nvim
```

## UNINSTALL

#### Linux / MacOS (unix)
rm -rf ~/.config/nvim\
rm -rf ~/.local/state/nvim\
rm -rf ~/.local/share/nvim

#### Flatpak (linux)
rm -rf ~/.var/app/io.neovim.nvim/config/nvim\
rm -rf ~/.var/app/io.neovim.nvim/data/nvim\
rm -rf ~/.var/app/io.neovim.nvim/.local/state/nvim

#### Windows CMD
rd -r ~\AppData\Local\nvim\
rd -r ~\AppData\Local\nvim-data

#### Windows PowerShell
rm -Force ~\AppData\Local\nvim\
rm -Force ~\AppData\Local\nvim-data
