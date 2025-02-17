## Commands
| Command               | Description                                         |
| --------------------- | --------------------------------------------------- |
| `cd -`                | switch to previous dir                              |
| `pwd`                 | print current dir                                   |
| `uname -a`            | print kernel, hostname, architecture, OS            |
| `uname -r`            | kernel release version                              |
| `readlink`            | outputs target of sym link                          |
| `type`                | is target builtin, alias, function, external        |
| `which`               | print the target path                               |
| `man -k` or `apropos` | search man pages for keyword                        |
| `history`             | show command history                                |
| `!num`                | run command number `num` from history               |
| `history -c`          | clear command history in the current session        |
| `history -w`          | write current session's history to the history file |
| `paste`               | merge lines of files horizontally                   |
| `od`                  | display file contents in octal, hex, etc.           |
| `split`               | split a file into smaller parts                     |
## Files
| Path      | Description              |
| --------- | ------------------------ |
| `/bin/sh` | symlink to default shell |
## Environment variables
| Name            | Description          |
| --------------- | -------------------- |
| `$SHELL`        | user's default shell |
| `$BASH_VERSION` | bash version         |
## Command Line Navigation & Editing

|Shortcut|Description|
|---|---|
|`Ctrl + a`|Move cursor to the **beginning** of the command|
|`Ctrl + e`|Move cursor to the **end** of the command|
|`Ctrl + u`|**Delete** from cursor to the beginning of the line|
|`Ctrl + k`|**Delete** from cursor to the end of the line|
|`Ctrl + w`|**Delete** the word before the cursor|
|`Alt + d`|**Delete** the word after the cursor|
|`Ctrl + y`|**Paste** (yank) the last deleted text|
|`Alt + b`|Move **backward** one word|
|`Alt + f`|Move **forward** one word|
|`Ctrl + b`|Move cursor **left** one character|
|`Ctrl + f`|Move cursor **right** one character|
|`Ctrl + l`|Clear the terminal (same as `clear`)|
|`Ctrl + r`|Reverse search command history|
|`Ctrl + s`|Forward search command history (may need `stty -ixon` to enable)|
|`Ctrl + p`|Recall the **previous** command (same as Up Arrow)|
|`Ctrl + n`|Recall the **next** command (same as Down Arrow)|
|`!!`|Run the last command again|
|`!word`|Run the most recent command starting with `word`|
|`^old^new`|Replace `old` with `new` in the last command and execute|


