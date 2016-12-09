darwinup-zsh-completion
=======================

A completion script for macOS's darwinup.

### Installation

Add the following to your `.zshrc`

    fpath=(/path/to/darwinup-zsh-completion $fpath)

Optionally, you might want to rebuild `.zcompdump`

    rm -f ~/.zcompdump; compinit
