# Vim

## Index
* [Vim Modes](#Vim-modes)
	- [Command Mode](#Command-Mode)
	- [Insert Mode](#Insert-Mode)
	- [Command Line Mode](#Command-Line-Mode)
	- [Visual Mode](#Visual-Mode)
* [Create New File](#Create-New-File)
* [Save File](#Save-File)
* [Read Only Mode](#Read-Only-Mode)
* [Edit Existing File](#Edit-Existing-File)
* [Getting Help](#Getting-Help)
* [Vim Editing](#Vim-Editing)
	- Insert(#Insert)
		+ [At The Beginning](#At-The-Beginning)
		+ [At The End](#At-The-End)
	- Open New Line(#Open-New-Line)
		+ [Below Current Line](#Below-Current-Line)
		+ [Above Current Line](#Above-Current-Line)
	- Substitute(#Substitute)
		+[Single Character Substitution](#Single-Character-Substitution)
		+[Line Substitution](#Line-Substitution)
	- Change(#Change)
	- Replace(#Replace)
	- Join(#Join)

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

## Read Only Mode

Use -R to open file in read-only mode.

> vim -R file_name.md

Alternatively we can also use view command

> view file_name.md

## Edit Existing File

```
Step 1: Open file in vim mode.
Step 2: Switch to inset mode and change some text.
Step 3: Save and quit using :wq.
Step 4: Quit without saving using :q!.
```

## Getting Help

Vim editor is command rich and it is not easy to remember every command. No worries, Vim can provide all the help we need using help command.

> :help

This command is used to access help.

To access help on specific topic the below command is used.

> :help topic

Here in above command replace topic with the topic you want help.

If we don't know the name we can still search for the topic using only a phrase.

> :helpgrep phrase (e.g. :helpgrep navigation)

## Vim Editing

### Insert

To insert any text use `i` key.

#### At The Beginning

If you are in the middle of a line and want to jump to the beginning of the line you can follow below steps.

```
Step 1: Press Esc.
Step 2: Press I.
```

This will take you to the starting of the current line in which you are working.

#### At The End

If you are in the middle of a line and want to jump to the end of the line you can follow below steps.

```
Step 1: Press Esc.
Step 2: Press A.
```

This will take you to the end of the current line in which you are working.

### Open New Line

#### Below Current Line

If you are in the middle of a line and want to open a new line below the current line then follow below steps.

```
Step 1: Press Esc.
Step 2: Press o.
```

This action will insert a new line below the current line and switch to insert mode.

#### Above Current Line

If you are in the middle of a line and want to open a new line above the current line then follow below steps.

```
Step 1: Press Esc.
Step 2: Press O.
```

This action will insert a new line above the current line and switch to insert mode.

### Substitute

#### Single Character Substitution

If you want to substitute a single character the follow below steps.

```
Step 1: Press Esc.
Step 2: Take the curser over the character which you want to substitute.
Step 3: Press s.
```

This action will delete the character and switch the Vim in Insert mode.

#### Line Substitution

If you want to substitute a whole line then do this.

```
Step 1: Press Esc.
Step 2: Take the curser on the line which you want to substitute.
Step 3: Press S.
```

This action will delete the entire line and switch the Vim in Insert mode.

