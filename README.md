## Cursor movement
```
h- move cursor left
j- move cursor down
k- move cursor up
l- move cursor right
w- jump forwards to the start of a word
W- jump forwards to the start of a word (words can contain punctuation)
e- jump forwards to the end of a word
E- jump forwards to the end of a word (words can contain punctuation)
b- jump backwards to the start of a word
B- jump backwards to the start of a word (words can contain punctuation)
0- jump to the start of the line
^- jump to the first non-blank character of the line
$- jump to the end of the line
G- go to the last line of the document
5G- go to line 5
```
#NOTE:Tip Prefix a cursor movement command with a number to repeat it. For example, 4j moves down 4 lines.

###Insert mode - inserting/appending text
```
i- insert before the cursor
10/9/2014 Vim Cheat Sheet - English
http://vim.rtorr.com/ 2/6
I- insert at the beginning of the line
a- insert (append) after the cursor
A- insert (append) at the end of the line
o- append (open) a new line below the current line
O- append (open) a new line above the current line
ea- insert (append) at the end of the word
Esc- exit insert mode

```

#Editing
```
r- replace a single character
J- join line below to the current one
cc- change (replace) entire line
cw- change (replace) to the end of the word
c$- change (replace) to the end of the line
s- delete character and substitute text
S- delete line and substitute text (same as cc)
xp- transpose two letters (delete and paste)
u- undo
Ctrl+ r- redo
.- repeat last command
```

#Cut and paste

```
yy- yank (copy) a line
2yy- yank (copy) 2 lines
yw- yank (copy) word
y$- yank (copy) to end of line
p- put (paste) the clipboard after the cursor
P- put (paste) before the cursor

dd- delete (cut) a line
2dd- delete (cut) 2 lines
dw- delete (cut) word
D- delete (cut) to the end of the line
d$- delete (cut) to the end of the line
x- delete (cut) character

```
##Exiting
```
:w- write (save) the file, but don't exit
:wq- write (save) and quit
:x- write (save) and quit
:q- quit (fails if there are unsaved changes)
:q!- quit and throw away unsaved changes
```


###Search and replace
```
/pattern- search for pattern
?pattern- search backward for pattern
n- repeat search in same direction
N- repeat search in opposite direction
:%s/old/new/g- replace all old with new throughout file
:%s/old/new/gc- replace all old with new throughout file with confirmations
```

## Tabs
```
:tabnewfilename or :tabnfilename - open a file in a new tab
Ctrl+ wt- move the current split window into its own tab
gtor :tabnextor :tabn- move to the next tab
gTor :tabprevor :tabp- move to the previous tab
#gt- move to tab number #
:tabmove #- move current tab to the #th position (indexed from 0)
:tabcloseor :tabc- close the current tab and all its windows
:tabonlyor :tabo- close all tabs except for the current one
```

###vim-cheat-sheet
https://vim.rtorr.com/
