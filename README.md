# My personal development setup in Linux

![image](screenshot.png)

**This setup only includes** `apt` **and** `dnf` **packages** 

<br>

## ⚠️ WARNING

Please fork this repository if you want to customize it on your own

<br>

## Installation

Clone this repository:
```
git clone https://github.com/Yncy0/wsl-dev-setup.git ~/.linux-dev-setup
```

If using SSH:
```
git clone git@github.com:Yncy0/linux-dev-setup.git ~/.linux-dev-setup && cd 
```

Run the script:
```
cd ~/.linux-dev-setup && chmod +x setup.sh && ./setup.sh
```

## ZSH
This projects is centralized in **zsh**.
If you wanted zsh to be your default shell, after installation run:

```
source ~/.zshrc
chsh -s $(which zsh)
```

If oh-my-zsh not showing, run this line:
```
zsh
```

⚠️ You might want to restart your terminal or reboot the system to apply the changes

<br>

## Project Includes:
- nvm
- tmux
- zsh && oh-my-zsh
- fastfetch
- Neovim
- Kitty && WezTerm

<br>

## Theme:
### You can choose different flavors, themes applied at Neovim, TMUX, and WezTerm
- catpuccin
- gruvbox

<br>

## NVM
- Node.JS
- npm
- pnpm

<br>

## Neovim:
- lazy.nvim 
- telescope
- treesitter

## mini.nvim:
- comments
- completion
- files
- icons

<br>

## TMUX:
- tpm

<br>

*Please if you have problems, contact me on my GitHub account: Yncy0, or open an issue on this repository. Thanks!*
