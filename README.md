# zsh-starter

A single `.zshrc` — Powerlevel10k, Zinit-managed plugins, fzf-powered previews, and a handful of aliases. Built and tested on Debian/Ubuntu.

<details>
<summary><b><code>Preview</code></b></summary>

[Preview](https://github.com/user-attachments/assets/c206a328-099e-4eca-934f-b51e971f9a40)

</details>

![GitHub stars](https://img.shields.io/github/stars/6aru/zsh-starter?style=for-the-badge)
![Zsh](https://img.shields.io/badge/ZSH-Stable-blue?style=for-the-badge)
  
## Install

```bash
sudo apt install -y zsh git curl wget fzf zoxide eza chafa unzip bat
cp ~/.zshrc ~/.zshrc.backup   # if you have one already
git clone https://github.com/6aru/zsh-starter.git
cp zsh-starter/.zshrc ~/.zshrc
chsh -s $(which zsh)
```
Log out and back in. Zinit and every plugin install themselves on first launch.

See the **[wiki](../../wiki)** for full setup details (including Arch/Fedora), the alias/plugin reference, and known limitations.

## What's in it

Powerlevel10k · Zinit · zsh-autosuggestions · zsh-syntax-highlighting · zsh-completions · fzf-tab · zoxide · eza · bat · chafa
