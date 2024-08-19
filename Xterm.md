Terminal emulator for the X window system.

---

#### Install

`$ sudo apt install xterm`

#### Customize

1. Create **.Xresources** file at home user

`$ vim $HOME/.Xresources`

2. Adding this lines:

```bash
! Font and font size
xterm*faceName: Hack
xterm*faceSize: 16

! Double click to select URLs
xterm*charClass: 33:48,36-47:48,58-59:48,61:48,63-64:48,95:48,126:48

! Colors
xterm*foreground: rgb:00/ff/00
xterm*background: rgb:00/00/00
```

3. Restart xinit or startx
