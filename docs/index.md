<!-- pandoc index.md -o index.html -->

<title>Bisqwit</title>
<link rel="stylesheet" href="bisqwit.css" type="text/css">


# Keymap

| FILE AND EXIT KEYS: | |
|--------|-------------------------|
| ^C:  | Exit without saving (will prompt for confirmation if unsaved changes)	|
| ^KD: | Save file (will prompt for filename to save to)	|
| ^KX: | Save and exit (will not prompt for filename, unless filename not known)	|
| ^KE: | Load new file without saving current one (will prompt for confirmation if unsaved changes; will prompt for filename to load)	|

<br>

| NAVIGATION KEYS: | |
|--------|-------------------------|
| ^V, pgdn:		| Go 1 page down |
| ^U, pgup:		| Go 1 page up |
| ^A, home:		| Go to beginning of line (column 1 or beginning of indent) |
| ^E, end:		| Go to end of line |
| ^B, left:		| Go left 1 character (if in column 1, go to end of previous line) |
| ^F, right:	| Go right 1 character (if in end of line, go to beginning of next line) |
| ^W:			| Scroll window up 1 line without moving the cursor |
| ^Z:			| Scroll window down 1 line without moving the cursor |
| ^KU, ctrl-pgup:| Go to beginning of file |
| ^KV, ctrl-pgdn:|  Go to end of file |
| ^KL:			| Prompt for a line number, and go to that line |
| ^G:			| Go to the matching parenthesis| 
| ctrl-left:	| Go to the previous word's beginning |
| ctrl-right:	| Go to the next word's beginning |
| ctrl-home:	| Go to the first displayed line (vertically only |
| ctrl-end:		| Go to the last displayed line (vertically only) |

<br>

| EDITING KEYS: | |
|--------|-------------------------|
| ^Y:		| Erase the line on which the cursor is currently |
| ^KB:		| Mark block begin at cursor location |
| ^KK:		| Mark block end at cursor location |
| ^KM:		| Move block to current cursor location |
| ^KC:		| Copy block to current cursor location |
| ^KY:		| Delete block | 
| ^K period:| Indent lines within the block by one tab stop (tab = 4) | 
| ^K comma:	| Unindent lines within the block by one tab stop (tab = 4) |
| Alt-Z:	| Undo |
| Alt-Y, Alt-R: | Redo |
| insert:	| Toggle insert/overwrite |
| ^D, delete: | Delete the character at cursor |
| ^H, backspace: | Go left by 1 character, then delete the character at cursor. If cursor was in the beginning of current line after indentation, erase enough spaces to unindent the line by 1 tab stop (tab = 4). |
| ^I, tab:	| Enter space characters until the cursor is at a tab stop (tab = 4) |
| ^M, ^J, enter: | Enter a newline character, and enough spaces to match the indent level of current line |
| Other:	|Enter the character. |

<br>

| MISCELLANEOUS KEYS: | |
|--------|-------------------------|
| ^K space:	| Display information about the character under the cursor |
| ^Q:		| Dummy |
| ^R:		| Redraw screen |
| F1:		| VGA mode change: Decrease rows by 1 |
| F2:		| VGA mode change: Increase rows by 1 |
| F3:		| VGA mode change: Decrease columns by 2 |
| F4:		| VGA mode change: Increase columns by 2 |
| F5:		| VGA mode change: Toggle 8pix / 9pix font |
| F6:		| VGA mode change: Toggle double-width, change the width 50%/200% accordingly to keep window size the same |
| shift-F6:	| VGA mode change: Toggle double-width, without changing width |
| F7:		| VGA mode change: Toggle double-width, adjust font/height to keep window size unchanged |
| shift-F7:	| VGA mode change: Toggle double-width, without changing height |
| F8, ^T:	| Invoke the VGA mode change dialog |
| F9:		| VGA mode change: Toggle pseudo-Commodore64 mode with PET font if fontheight=8 (right now broken, sorry!) |
| F10:		| VGA mode change: Toggle all-caps mode (use in conjunction with C64 mode) |

<br><br>