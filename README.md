# emacs

## installation via github
- [emacs](https://github.com/doomemacs/doomemacs/blob/master/docs/getting_started.org#ubuntu)
- [doom-emacs](https://github.com/doomemacs/doomemacs#install)

## installation via my steps
```bash
# install emacs via snap (Ubuntu OS)
sudo add-apt-repository ppa:kelleyk/emacs
sudo apt-get update
sudo apt install emacs (or sudo snap install emacs --classic)

# install Doom’s other dependencies
sudo apt-get install ripgrep fd-find

# install doom
git clone --depth 1 https://github.com/doomemacs/doomemacs ~/.config/emacs
~/.config/emacs/bin/doom install

# add the code below into .bashrc
export PATH=$PATH:$HOME/.config/emacs/bin

# remove .emacs.d folder
sudo rm -r .emacs.d
```
