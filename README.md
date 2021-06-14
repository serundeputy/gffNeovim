# neovim

This is my config file for [neovim](https://github.com/neovim/neovim) it travels with me from computer to computer. You are welcome to use it too.

## Install neovim

* `brew install neovim`

or use any of the methods available in the /neovim/neovim github repo.

Update the `pynvim` plugin if necessary:

```bash
python3 -m pip install --user --upgrade pynvim
```

## Usage

Clone:

```bash
git clone git@github.com:serundeputy/gffNeovim.git
```

I usually clone it to my home directory, but you can put it where you like. Then I symlink `~/.config/nvim/init.vim` to `~/gffNeovim/gff.init.vim`.

Create the `nvim` config directory if it does not exist:

```bash
mkdir -p ~/.config/nvim
```

```bash
ln -s ~/gffNeovim/gff.init.vim ~/.config/nvim/init.vim
```

Enjoy using neovim!
