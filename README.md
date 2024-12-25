#### Install ZSH  
```sudo apt install zsh```  

#### Set ZSH as default shell 
###### For Ubuntu/Pop!_OS/Debian-based systems:
> Go to Preferences > your terminal profile > Command > check "Run custom command instead of my shell" and set it to ```zsh```

#### Install Oh My Zsh
```sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```  

#### Install Plugins
```
git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
```

```plugins=(git zsh-autosuggestions zsh-syntax-highlighting)```

#### Download and install Fira Mono Nerd Font
https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/FiraMono/Regular

#### Install Powerlevel10k and set theme 
```
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```
```
ZSH_THEME="powerlevel10k/powerlevel10k"
```
