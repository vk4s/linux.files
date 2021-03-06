# TMUX (.tmux.conf)

### Install TPM

[Installation Guides](https://github.com/tmux-plugins/tpm#installation)

Reload TMUX environment so TPM is sourced:

**type this in terminal if tmux is already running**

```$
tmux source ~/.tmux.conf
```

check [.tmux.conf](.tmux.conf) for sample.

Make symlink to `/root/` as

```$
sudo ln -s /home/ubuntu/.tmux.conf /root/
```

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

Reinstall for **`root`** user.

---

# NANO

Detailed instructions can be found [HERE](https://linuxhint.com/configure_nano_text_editor_nanorc/)

Or download `.nanorc` from this repo

Make a symlink to `/root/` to use as:

```$
sudo ln -s /home/ubuntu/.nanorc /root/
```

---

# VIM Configuration

first create `~/.vim/autoload` and cd into it.
Then run

```$
wget https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

Copy `.vimrc` to `~/` (user directory)
Them open `vim` and run `:PlugInstall`

<br>
<hr>
<br>
<div align='center'>

[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
![made-using-Markdown](https://img.shields.io/badge/Made%20using-Markdown-1f425f.svg)
[![made-by-Vikash](https://img.shields.io/badge/with%20💖%20by-Vikash-cc62c3.svg)](http://vkash.lorbic.com)

</div>
