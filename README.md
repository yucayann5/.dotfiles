## How to use

1. Fork this repository.

2. Clone.

```shellsession
$ git clone git@github.com:${YOUR_NAMESPACE}/.dotfiles.git ~/.dotfiles
$ cd ~/.dotfiles
$ git submodule update --init --recursive
```

3. Create symlinks.

First, go to your home directory.

```shellsession
$ cd
```

**Use `zsh`** with `~/.zshrc`.

```shellsession
$ ln -s .dotfiles/zsh/.zshrc .
$ chsh -s /bin/zsh
Changing shell for YOUR_NAME.
Password for YOUR_NAME: 
```

**Use `vim`** with `~/.vimrc` and `~/.vim` directory.

```shellsession
$ ln -s .dotfiles/vim/.vim .
$ vim
```

And run `:BundleInstall` on your vim.
