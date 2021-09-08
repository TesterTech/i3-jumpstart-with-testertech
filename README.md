# i3-jumpstart-with-testertech
Code for the YT video https://www.youtube.com/watch?v=XeGjeEPlnQM

## Installation (Fedora)
```
sudo dnf install -y i3 i3status dmenu i3lock rofi feh light redshift-gtk redshift copyq arandr 
```
### i3 volume
- https://github.com/hastinbe/i3-volume

## Aliasses
- You can put these in your ~/.bashrc (or ~/.bash_aliasses) it helps speed up the 'tinkering' a lot. 
```
alias rxconf='vim ~/.Xresources'
alias vimrc='vim ~/.vimrc'
alias i3conf='vim ~/.config/i3/config'
alias bashrc='vim ~/.bashrc'
alias polyconf='vim ~/.config/polybar/config'
alias rexvt='xrdb ~/.Xresources && pkill urxvt'
```

## Configs
- i3 config
- .Xresources
- Polybarconfig
- Compton

### OPTIONAL i3 Gaps
- Basically i3 but with space between the tiles 
- If you want to use i3 Gaps in stead of i3, do as below:
```
sudo dnf remove i3
sudo dnf copr enable fuhrmann/i3-gaps
sudo dnf update -y
sudo dnf install -y i3-gaps
```

and uncomment the i3 config:

```
gaps inner 7
gaps outer 7
```




## References
- [Video from Aline](https://www.youtube.com/watch?v=Api6dFMlxAA)
- [i3wm docs](https://i3wm.org/docs/userguide.html)
- [i3 refcard](https://i3wm.org/docs/refcard.html)
- [Arch Wiki on i3](https://wiki.archlinux.org/title/i3)

## Youtubers with more i3 content
- [Budlabs lots of content on i3 also on his own project i3ass](https://www.youtube.com/c/dubbeltumme/)
- [CodeCast 3 part series on i3](https://www.youtube.com/playlist?list=PL5ze0DjYv5DbCv9vNEzFmP6sU7ZmkGzcf)
- [Luke Smith i3 ricing](https://www.youtube.com/playlist?list=PL-p5XmQHB_JTcMSvPmXMzNe7ZPMxEx_Oz)