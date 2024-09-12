* "Esc" : normal mode
* "Esc" then u: undo the latest changes
* ":" : indicate that you are about to write a command
* ":q!" : quit without saving changes
* ":wq" : save and quit a file 



# Deletion commands

"dw": deletes the word (put cursor at the beginning of the word)
"d$": deletes to the end of the line (start from the end of a correct line)
"de": deletes from the cursor to the end of the word

Typing a number before a motion repeats it that many times:

"2w": moves the cursor 2 words forward 
"3e": moves the cursor to the end of the third word
"0": move to the start of the line

Can add numbers between an operator and a motion
Can repeat a motion by adding a number before it

"dd": deletes the whole line and stores it in a Neovim register

"u": undo previous actions
"U": undo all changes on a line
"Cntrl-r": undo all the undo's

"p": copies a deleted line using "dd" right below where your cursor is.

"r": replace a character, so type r then the new character to be placed

"ce": change until the end of a word

The change operator workds in the same way as delete command: c [number] motion

# Cursor location and file status

"Cntrl-g": shows your location in a file and the file status
"nb_line G": jump to the line nb_line.
"G": aller a la fin du fichier
"gg": aller au debut du fichier

"/": followed by a phrase to search for the phrase, to search for the same phrase again type "n", in opposite direction "N"
"?": to search for a phrase in the backward direction (so starting from the end of the file)
