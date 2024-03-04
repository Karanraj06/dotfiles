# dotfiles

This repository contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

### Stow

```
brew install stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
git clone https://github.com/Karanraj06/dotfiles
cd dotfiles
```

then use GNU stow to create symlinks

```
stow .
```