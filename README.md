# zsh-commands
## Here you can find useful shorcuts for zsh

HomeBrew without admin permission
```
mkdir ~/homebrew
curl -L https://github.com/Homebrew/brew/tarball/master | tar xz --strip 1 -C ~/homebrew
```
Add HomeBrew to you PATH 
```
nano ~/.zshrc
export PATH="$HOME/homebrew/bin:$PATH"
source ~/.zshrc
```
Then you can check if its running:
```
brew --version
```

