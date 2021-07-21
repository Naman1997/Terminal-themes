# Windows terminal theme

# ![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTzH2tRzADePJGqGeir-NDrKF96YIw8S_Xl6w&usqp=CAU)


Create a PROFILE file if it does not already exists and paste the contents of [PROFILE](https://github.com/Naman1997/Terminal-themes/blob/main/Windows/PROFILE) file in it.
```
notepad $PROFILE
```


Follow [this](https://docs.microsoft.com/en-us/windows/terminal/tutorials/powerline-setup) guide to setup your theme.


You will need to install the following from the above documentation to apply the provided theme correctly:
- posh-git
- oh-my-posh
- PSReadline
- Cascadia Code PL

We will use material theme that's mentioned in the PROFILE file. For more themes, go [here](https://github.com/JanDeDobbeleer/oh-my-posh/tree/main/themes).


For "Cascadia Code PL" dependency:
- Download the latest zip from [here](https://github.com/microsoft/cascadia-code/releases)
- Extract the zip
- Install CascadiaCode-*\ttf\CascadiaCodePL.ttf


Now, take a backup of your settings.json by selecting Settings (Ctrl+,) from your Windows Terminal dropdown menu. This can also be done using the settings UI if you have it enabled. Copy the settings.json file from this repo, paste it in your settings.json and hit save. Your settings should be updated after restarting the terminal.
