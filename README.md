# dotfiles

To symlink the config files to the correct location simply run: stow --target=~/ _folder\_name_, or use `make all` to stow all files in the home directory.
  
This will symlink all the contents inside _folder\_name_ to the same structure
inside the folder, but in the parent directory of where the stow command was run.

## Shell

Zsh: <https://github.com/ohmyzsh/ohmyzsh>

config: `~/.zshrc`

##### Syntax highlightning

zsh-syntax-highlightning: <https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md>

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

Install: `git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`

## EZA
Replaces the traditional ls command.

Eza: <https://github.com/eza-community/eza>

### Zoxide
Replaces CD.

<https://github.com/ajeetdsouza/zoxide>

Install by running `curl -sSfL https://raw.githubusercontent.com/ajeetdsouza/zoxide/main/install.sh | sh`

## fzf
Fuzzy finder

```
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

## LazyGit
Lazy is good.

Install on Ubuntu:
```
LAZYGIT_VERSION=$(curl -s "https://api.github.com/repos/jesseduffield/lazygit/releases/latest" | grep -Po '"tag_name": "v\K[^"]*')
curl -Lo lazygit.tar.gz "https://github.com/jesseduffield/lazygit/releases/latest/download/lazygit_${LAZYGIT_VERSION}_Linux_x86_64.tar.gz"
tar xf lazygit.tar.gz lazygit
sudo install lazygit /usr/local/bin
```

