## Install

This readme is specifically for installing this config of oh-my-zsh in arch linux. Some commands might be different depending on your distro.

```
sudo pacman -S wget zsh
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-history-substring-search ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-history-substring-search
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```


Now cd into the dir where you keep your github repos.


```
git clone https://github.com/Naman1997/Terminal-themes.git
cp Terminal-themes/zsh/.z* ~
```


## Uninstall


To uninstall:
```
uninstall_oh_my_zsh && rm -rf .z*
```
