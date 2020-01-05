## ZSH Setup

**Install ZSH**

```
sudo apt-get install zsh -y
```

**Make ZSH default shell**

```
chsh -s $(which zsh)
```

**Install OhMyZsh**

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

**Copy .zshrc**

```
curl 'https://raw.githubusercontent.com/93gaurav93/dotfiles/master/.zshrc' > $HOME/.zshrc
```

**Copy .zsh_aliases**

```
curl 'https://raw.githubusercontent.com/93gaurav93/dotfiles/master/.zsh_aliases' > $HOME/.zsh_aliases
```

** Install zsh-autosuggestions plugin**

```
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.zsh/zsh-autosuggestions
```

**Install spaceship theme**

```
git clone https://github.com/denysdovhan/spaceship-prompt.git "$ZSH_CUSTOM/themes/spaceship-prompt"

ln -s "$ZSH_CUSTOM/themes/spaceship-prompt/spaceship.zsh-theme" "$ZSH_CUSTOM/themes/spaceship.zsh-theme"
```

**Restart terminal**

```
zsh
```



