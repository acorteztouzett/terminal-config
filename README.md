
# Terminal Config

First check which terminal are you using. To change from bash to zsh use:





Check if zsh is running:

```zsh
echo $0
```
To change from bash to zsh use either of them:
```zsh
chsh -s /bin/zsh
chsh -s /usr/local/bin/zsh
```
Next, install iTerm as new terminal:

[Install iTerm2 here](https://iterm2.com/)

Install Oh-My-Zsh:
```zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
Install Powerlevel10k and configure:
```zsh
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```
---
## Extras
```zsh
vim ~/.zshrc
```
Example of aliases: 
```zsh
alias vsc="open -a Visual\ Studio\ Code"
```


Plugins
- git
- zsh-autosuggestions
- zsh-syntax-highlighting
- Cross platform
```zsh
git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
```


Copy on .zshrc and to restart:
```zsh
source ~/.zshrc
```
