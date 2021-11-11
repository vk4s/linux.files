# TMUX (.tmux.conf)

### Install TPM

[Installation Guides](https://github.com/tmux-plugins/tpm#installation)

Reload TMUX environment so TPM is sourced:

**type this in terminal if tmux is already running**

```$
tmux source ~/.tmux.conf
```

check [.tmux.conf](.tmux.conf) for sample.

---

# ZSH

Install **zsh**

```$
sudo apt install zsh
```

Install **oh-my-zsh**

```$
sh -c "$(wget https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh -O -)"
```

##### Change theme to `gnzh`

### Set `zsh` to default shell

-- for normal user --

```$
sudo chsh -s $(which zsh) <username>
```

-- for root --

```$
sudo chsh -s $(which zsh)
```

---

# NANO

Detailed instructions can be found [HERE](https://linuxhint.com/configure_nano_text_editor_nanorc/)

Or download `.nanorc` from this repo

---

# VIM Configuration

first create `~/.vim/autoload` and cd into it.
Then run

```$
wget https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

Copy `.vimrc` to `~/` (user directory)
Them open `vim` and run `:PlugInstall`
