# BASIC ZSH OPTION
- AUTO SUGGESTION
- HIGHLIGHTING

# Setup

```bash
sudo apt-get update
sudo apt-get upgrade -y
sudo apt-get install zsh -y
curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh | sh /dev/stdin
```


```bash
sudo chsh -s $(which zsh)
```

```bash
# clone Zsh Autosuggestions, Syntax Highlighting
git clone https://github.com/zsh-users/zsh-autosuggestions ~/.oh-my-zsh/custom/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ~/.oh-my-zsh/custom/plugins/zsh-syntax-highlighting
```

```bash
zsh
```

```bash
cp .zshrc ~/
source ~/.zshrc
```

## Optional
```bash
sudo apt-get install nginx -y
# apt-get install konsole -y
sudo apt-get install docker-compose -y
sudo usermod -aG docker $USER
sudo newgrp docker

```
