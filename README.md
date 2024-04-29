# dotfiles

To symlink the config files to the correct location simply run: stow --target=~/ _folder\_name_, or use `make all` to stow all files in the home directory.
  
This will symlink all the contents inside _folder\_name_ to the same structure
inside the folder, but in the parent directory of where the stow command was run.

## Shell

Zsh: <https://github.com/ohmyzsh/ohmyzsh>

config: `~/.zshrc`

##### Syntax highlightning

zsh-syntax-highlightning: <https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md>

Note: Probably only need to clone the repository, since it is already sourced in the `.zshrc` file in this repo.

## Prompt

Starship: <https://starship.rs/>

config: `~/.zshrc`

## Editor

Neovim: <https://github.com/deivard/kickstart.nvim>

config: `~/.config/nvim/init.lua`

## Terminal multiplexer

Tmux: <https://github.com/tmux/tmux/wiki/Installing>

config: `~/.tmux.conf`

##### Tmux plugin manager

TPM: <https://github.com/tmux-plugins/tpm>
