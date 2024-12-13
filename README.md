## Dotfiles Instructions

This repository contains the dot files for my system


### Tools
Installing terminal

```zsh
yay -S alacritty
```

### Dependencies

```zsh
yay -S git
```
Installing stow dot files manager

```zsh
yay -S stow
```

### Installation

First, checkout the dot files repository in my $HOME directory using git

```zsh
git clone git@github.com:cmanon/dotfiles.git Dotfiles
cd Dotfiles
```

Then use stow to create the symlinks

```zsh
stow .
```

Install and configure the terminal multiplexer
```zsh
yay -S tmux
```

Install the tmux plugin manager
```zsh
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

[Vide About Tmux](https://www.youtube.com/watch?v=DzNmUNvnB04)