ZSH Setup  
Install ZSH  

bash
Copy code
sudo apt install zsh
chsh -s $(which zsh)
Install Oh My Zsh

bash
Copy code
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
Install Plugins

bash
Copy code
git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
Update .zshrc:

bash
Copy code
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
Install Nerd Font
Download and install Fira Mono Nerd Font.

Install Powerlevel10k

bash
Copy code
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
Update .zshrc:

bash
Copy code
ZSH_THEME="powerlevel10k/powerlevel10k"
