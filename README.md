# WSL - OH-MY-ZSH Setup

This is simple repository that contains two simple scripts that I use to setup a Linux distribution on WSL, and installs oh-my-zsh shell with some plugins and tools. It also uses Github CLI to automatically generate and configure your SSH authentication and signing keys.

## wsl-dist-install.ps1

- This is a powershell script that assumes that you already have WSL enbled on your Windows machine.
- After you follow the prompts to setup your image, run ```exit``` on the Linux console that will open, so that the powershell script can install the following tools and plugins on the image:

### Tools

- ```Github CLI``` - The Github CLI is installed to setup the authentication and signing keys automatically.
- ```Starship```   - A customizable prompt for any shell. [Starship](https://starship.rs/)

### Plugins

- ```zsh-autosuggestions```
- ```zsh-syntax-highlighting```
- ```zsh-completions```
- ```zsh-history-substring-search```
- ```autoupdate```

### Font

- ```Fira Code Nerd```

## Requirements

| Requirement | Version |
| ----------- | ------- |
| WSL | 2 |

## MIT License

This project is licensed under the terms of the MIT license. For more details, see the [LICENSE](LICENSE) file in the project root.
