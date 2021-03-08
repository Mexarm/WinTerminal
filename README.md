# WinTerminal

1) Install Windows Terminal
https://github.com/microsoft/terminal

2) Setup PowerLine
https://docs.microsoft.com/en-us/windows/terminal/tutorials/powerline-setup

3) Download and install a Nerd Font
https://www.nerdfonts.com/font-downloads

4) open windows terminal and goto settings [Ctrl+,]

Change the name of your font 

```
  "fontFace":  "CaskaydiaCove NF",
```
 and save
 
 5) choose your prompt theme:
 https://ohmyposh.dev/docs/themes/
 
 ```
notepad $PROFILE
```
 set your theme in your profile file and save it 
```
...
...
Set-PoshPrompt -Theme <change-me>
```
 
 6) finally close and relaunch your terminal
