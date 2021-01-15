What is Vim?
Vim stands for

Commands
:q      then enter  To quit vim
:w      writes current state to file
:wq     save and exit
:q! exits without saving or overwrite


Vim has modes and starts with command mode
i   gets you into insert mode
esc takes you back to command mode
dd  delete a line in command mode also copies to your clip board
3dd deletes 3 lines
u   undoes damage (outside of command line)
control + r     to redo (outside of command)
j&k    take you up and down
h&l   take you left and right
G and gg top and bottom of the page
. redoes whatever you just did
$   takes you to the end of a line
yy copies the line to your clipboard
p  pastes below the line
P  pastes above the cursor
V    takes you into visual mode



/example    finds matches (n to search down / N to search up)
:%s/example/replacement/gc            search n replace in command mode
        (g stands for greedy which changes all)
        (c stands for confirm)

