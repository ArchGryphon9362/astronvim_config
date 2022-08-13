# AstroNvim Config Files :)

## To use run the following commands:

Install neovim v0.7.2
Find out how on this website: [GitHub - neovim/neovim - Installing Neovim](https://github.com/neovim/neovim/wiki/Installing-Neovim)

Clone the AstroNvim repo

```sh
git clone https://github.com/AstroNvim/AstroNvim ~/.config/nvim
```

Clone the repo

```sh
git clone git@github.com:ArchGryphon9362/astronvim_config ~/.config/nvim/lua/user
```

Use unattended mode, to install all the requirements

```sh
nvim  --headless -c 'autocmd User PackerComplete quitall' -c 'PackerSync'
```
