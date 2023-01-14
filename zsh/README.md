## Install

This guide is specifically for installing this config of oh-my-zsh in arch linux. Some commands might be different depending on your distro.

```
sudo pacman -S wget zsh figlet inetutils
sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

Allow zsh to be your default shell

Run the commands below

```
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-history-substring-search ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-history-substring-search
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

Now cd into the dir where you keep your github repos.

```
git clone https://github.com/Naman1997/Terminal-themes.git
cp Terminal-themes/zsh/.z* ~
rm -rf Terminal-themes/
```


## Uninstall


Make sure that you do not have any other files that match ~/.z* before running the 'rm' command below.
```
uninstall_oh_my_zsh && rm -rf ~/.z*
```
