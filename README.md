# AstroNvim Configuration By Critiek 🙂

A user configuration for [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## 🛠️ Installation

### Make a backup of your current nvim and shared folder if you use NeoVim

Windows (PowerShell 7+)
```shell
mv $env:LOCALAPPDATA/nvim $env:LOCALAPPDATA/nvim.bak
```

Linux/MacOS
```shell
mv ~/.config/nvim ~/.config/nvim.bak
mv ~/.local/share/nvim ~/.local/share/nvim.bak
```

### Clone AstroNvim

Windows (PowerShell 7+)
```shell
git clone https://github.com/AstroNvim/AstroNvim $env:LOCALAPPDATA/nvim
```

Linux/MacOS
```shell
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
```

### Clone the repository

Windows (PowerShell 7+)
```shell
git clone https://github.com/Critiek/critiek-astronvim $env:LOCALAPPDATA/nvim/lua/user
```

Linux/MacOS
```shell
git clone https://github.com/Critiek/critiek-astronvim ~/.config/nvim/lua/user
```

### Start Neovim

```shell
nvim
```

### One Command to do Everything (DELETES OLD NEOVIM CONFIG!!!)

Windows (PowerShell 7+)
```shell
rm -force -r $env:USERPROFILE\AppData\Local\nvim\ && rm -force -r $env:USERPROFILE\AppData\Local\nvim-data\ && git clone https://github.com/AstroNvim/AstroNvim $env:LOCALAPPDATA/nvim && git clone https://github.com/Critiek/critiek-astronvim $env:LOCALAPPDATA/nvim/lua/user
```

Linux/MacOS
```shell
sudo rm -rf ~/.config/nvim && sudo rm -rf ~/.local/share/nvim && git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim && git clone https://github.com/Critiek/critiek-astronvim ~/.config/nvim/lua/user
```
