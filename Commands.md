Start Vim
- $vim

Quit Vim
- :q

Create new file or open existing file
- :edit file_name.extension


Save file
- :w

Save and quit
- :wq

Quit without saving
- :q!


Read Only Mode
- vim -R file_name.md

OR

- view file_name.md

Getting Help
- :help
- :help topic_name
- :helpgrep phrase

Insert and Navigation Operation
|Command            |Description                                                                                        |
|-------------------|---------------------------------------------------------------------------------------------------|
|I                  |Take cursor to the beginning of the line.                                                          |
|A                  |Take cursor to the end of the line.                                                                |
|O                  |Open a new line above the current line.                                                            |
|o                  |Open a new line below the current line.                                                            |
|s                  |Delete for substitution of a single character and switch to Vim mode.                              |
|S OR cc            |Delete for substitution of a whole line and switch to Vim mode.                                    |
|C                  |Delete a portion of a line for substitution after the cursor.                                      |
|r                  |Replace a single character and make it editable without switching to Vim mode.                     |
|R                  |Replace a portion of line and make it editable from cursor position without switching to Vim mode. |
|J                  |Join to lines.                                                                                     |
|h                  |Move left.                                                                                         |
|j                  |Move down.                                                                                         |
|k                  |Move up.                                                                                           |
|l                  |Move right.                                                                                        |
|0                  |Jump to the beginning of a current line.                                                           |
|:0                 |Jump to the beginning to the file.                                                                 |
|$                  |Jump to the end of a current line.                                                                 |
|:$                 |Jump to the end of a the file.                                                                     |
|ctrl + f           |Scroll down entire page.                                                                           |
|ctrl + b           |Scroll up entire page.                                                                             |

Navigation
- 10j (Move curser down by 10 position)
- 5k (Move curser up by 5 position)
- 7h (Move curser left by 7 position)
- 3l (Move curser right by 3 position)

Swap file name
- :swapname

Cut, Copy and Paste

|Command            |Description                                                                                        |
|-------------------|---------------------------------------------------------------------------------------------------|
|dw                 |Cut word from cursor position including the character.                                             |
|D                  |Cut line after cursor position including the character on that position.                           |
|dd                 |Cut entire line                                                                                    |
|p                  |Paste character or line after cursor position.                                                     |
|P                  |Paste character or line before cursor position.                                                    |
|Y or yy            |copy entire line.                                                                                  |

Multiline Editing operation
- 2dd (Cut 2 lines from the line where cursor is positioned.)
- 2D (Cut 2 lines from the cursor position.)
- 3Y (Copy or yank 3 lines from cursor position.)

Undo
- u

Redu
- ctrl + r

OR

- :red

