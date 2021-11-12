# dotfiles

This is the repo in which I keep my dotfiles backed up.

To use them you clone this repository to a local folder - for example `~/source/dotfiles`.

```console
$ git clone https://github.com/wulfland/dotfiles.git ~/source/dotfiles
```

Then link them to the home folder using the `-s` option:

```console
$ ln -s ~/source/dotfiles/.zshrc ~/.zshrc
$ ln -s ~/source/dotfiles/.vimrc ~/.vimrc
$ ln -s ~/source/dotfiles/.gitconfig ~/.gitconfig
```

The iTerm config is configured to store its settings automatically in the git repo.
