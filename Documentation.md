# Vim

## Index
* [Vim Modes](#Vim-modes)
* [Create New File](#Create-New-File)
* [Save File](#Save-File)

## Vim Modes

Vim Supports multiple modes.

### Command Mode 

We can use different commands in this mode i.e. copy, paste, delete, replace and many more.

### Insert Mode 

We can use this mode to enter/edit text. To switch from default command to insert mode press i key.

### Command Line Mode 

Command in this mode starts with colon(:). above quit command is entered in this mode. Any Vim command starting with colon indicates that we are executing that command in command line mode.
	- To switch from command mode to this mode use colon.
	- To switch from insert mode to this mode press escape and type colon.

### Visual Mode 

In this mode we can visually select text and and run command on selected section.
	- To switch from command mode to visual mode type v.
	- To switch from any other mode to visual mode, first switch back to command mode by pressing escape, then type v

## Create New File

Following command is used to create a new file in Vim. If the file is already exist then it opens the file in Vim mode.

> :edit file_name.extension

## Save File

> :w

Above commmand is used to save the changes.

> :wq

Above command is used to save the changes and quit Vim.