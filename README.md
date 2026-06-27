# Baru ZSH

![GitHub stars](https://img.shields.io/github/stars/6aru/zsh-starter?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/6aru/zsh-starter?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/6aru/zsh-starter?style=for-the-badge)
![Zsh](https://img.shields.io/badge/ZSH-Stable-blue?style=for-the-badge)

A modern ZSH configuration built around:

* Powerlevel10k
* Zinit
* zsh-autosuggestions
* zsh-syntax-highlighting
* zsh-completions
* fzf-tab
* zoxide
* eza
* bat

Fast, clean, beginner friendly and suitable for Debian, Arch and other Linux distributions.

---

## Preview

![Preview](Priview.mp4)

---

## Features

* Self-installing Zinit
* Powerlevel10k prompt
* Git integration
* Smart command suggestions
* Syntax highlighting
* Fuzzy completions
* Fast directory jumping with Zoxide
* Beautiful file listings with Eza
* Better cat with Bat
* Useful aliases

---

## Requirements

### Debian / Ubuntu

```bash
sudo apt install -y \
zsh git curl wget \
fzf zoxide eza bat \
ripgrep fd-find
```

### Arch Linux

```bash
sudo pacman -S \
zsh git curl wget \
fzf zoxide eza bat \
ripgrep fd
```

### Fedora

```bash
sudo dnf install \
zsh git curl wget \
fzf zoxide eza bat \
ripgrep fd-find
```

---

## Installation

### Backup Existing Configuration

```bash
cp ~/.zshrc ~/.zshrc.backup
```

### Clone

```bash
git clone https://github.com/6aru/zsh-starter.git
```

### Install

```bash
cp zsh-starter/.zshrc ~/.zshrc
```

### Set ZSH as Default Shell

```bash
chsh -s $(which zsh)
```

Log out and back in.

---

## Aliases

| Command | Description                      |
| ------- | -------------------------------- |
| ls      | Eza with icons                   |
| ll      | Detailed listing with Git status |
| la      | Show hidden files                |
| lt      | Tree view                        |
| c       | Clear terminal                   |
| vim     | Launch Neovim                    |
| update  | Update Debian packages           |
| cat     | Bat replacement                  |
| ..      | Go up one directory              |
| ...     | Go up two directories            |
| ....    | Go up three directories          |

---

## Included Plugins

| Plugin                  | Purpose               |
| ----------------------- | --------------------- |
| Powerlevel10k           | Prompt                |
| zsh-autosuggestions     | Command suggestions   |
| zsh-syntax-highlighting | Syntax highlighting   |
| zsh-completions         | Extra completions     |
| fzf-tab                 | Fuzzy completion menu |
| zsh-you-should-use      | Alias recommendations |

---

## Tools

### Zoxide

Jump instantly:

```bash
z Downloads
z Projects
```

### FZF

Search interactively:

```bash
CTRL + R
```

### Eza

Beautiful listings:

```bash
ll
lt
```

---

## License

MIT

---

If this project helped you, please consider giving it a ⭐ on GitHub.
