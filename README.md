# homebrew setup
- https://brew.sh/
- https://formulae.brew.sh/cask/iterm2
```
vi ~/.zshrc
export PATH="/opt/homebrew/bin:$PATH"
source ~/.zshrc
```

# install [powerlevel10k](https://github.com/romkatv/powerlevel10k)
```shell
brew install powerlevel10k
echo "source $(brew --prefix)/share/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
```

# install [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting?tab=readme-ov-file)
```
brew install zsh-syntax-highlighting
echo "source $(brew --prefix)/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh" >> ${ZDOTDIR:-$HOME}/.zshrc
```

# import color profile
- iTerm2 > settings > Profiles > color > Other actions > import json file

# vscode theme
- https://github.com/azemoh/vscode-one-monokai
