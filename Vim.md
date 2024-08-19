**Is a text editor that is upwards compatible to Vi.  It can be used to edit all kinds of plain text.  It is especially useful for editing programs**

---

### Installation
`$ sudo apt install vim-gtk3`
or
`$ sudo apt install vim`

### Usage
Open vim
`$ vim`

Create a new file
`$ vim newFile.txt`

Open an existing file
`$ vim file.txt`

**Command Mode** Open a file:
`:open Scripts/text.sh`

### Keyboard
Split screen vertical:
\<C-w>v

Split screen at bottom
\<C-w>s

Move to the left, right, up and down window:
\<C-w>l
\<C-w>h
\<C-w>k
\<C-w>j

**Increase o reduce windows size in vim**
Increase/reduce the width:
\<C-w> >
\<C-w> <

Increase/reduce the height:
\<C-w> +
\<C-w> -

Reset the width and height of windows:
\<C-w> =

### Termux
The following shortcuts are available when using termux with  a hardware keyboard by combining them with Ctrl+Alt
C -> Create a new session
R -> Rename current session
N -> Next session
P -> Previous session
Right arrow -> Open drawer
Left arrow -> Close drawer 
M -> Show menu
U -> Select URL
V -> Paste
+/- -> Adjust text size
1-9 -> Go to numbered session
K -> Enable / Disable soft keyboard