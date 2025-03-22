# Spydur Linux Commands
| Shortcut Name | Alias / Shortcut Syntax       | Function Description                         | How to Use                                                             |
|---------------|-------------------------------|----------------------------------------------|------------------------------------------------------------------------|
| ll            | `alias ll='ls -l'`            | Lists directory contents in long format      | Type `ll` in the terminal to view files in a list view                 |
| vi            | `alias vi='/usr/bin/vim'`     | Opens Vim instead of default vi              | Type `vi filename` to open/edit with Vim                               |
| back          | `alias back='cd -'`           | Goes back to the previous directory          | Type `back` to return to the last visited directory                    |
| rm            | `alias rm='rm -i'`            | Prompts before deleting files                | Type `rm filename` and confirm before deletion                         |
| mv            | `alias mv='mv -i'`            | Prompts before overwriting files             | Type `mv source dest` and confirm before overwrite                     |
| $sw           | `export sw=/usr/local/sw`     | Sets a variable pointing to /usr/local/sw    | Use `$sw/bin/tool` or `cd $sw` instead of full path                    |
| $hpclib       | `export hpclib=$sw/hpclib`    | Sets a variable pointing to HPC library      | Use `$hpclib/module` or `cd $hpclib` instead of full path              |
| !!            | `!!`                          | Repeats the last command                     | Type `!!` to run the previous command again                            |
| !<string>     | `!<string>`                   | Runs last command starting with string       | For example, `!git` reruns last command starting with "git"            |
| !n            | `!n`                          | Runs command number *n* from history         | For example, `!42` runs command #42 from the `history` output          |
| Ctrl + R      | `Ctrl + R`                    | Reverse search through command history       | Press `Ctrl + R` and start typing to search previous commands          |
| Ctrl + D      | `Ctrl + D`                    | Logs out of terminal or ends input (EOF)     | Press `Ctrl + D` at empty prompt to log out, or to end `cat`, `python` |
| Ctrl + C      | `Ctrl + C`                    | Cancels a running process                    | Press `Ctrl + C` to stop a command or script that’s running            |
| Ctrl + L      | `Ctrl + L`                    | Clears the terminal screen                   | Same as `clear`, but faster                                            |
| TAB           | `TAB`                         | Auto-completes file/command names            | Press `TAB` to autocomplete path or command; double-TAB for suggestions|
| history       | `history`                     | Shows command history                        | Type `history` to see your past commands with numbers                  |
| htop          | `htop`                        | Interactive system monitor                   | Run `htop` to view real-time CPU/memory/process usage (may need to install) |
| tree          | `tree`                        | Displays directory structure as a tree       | Run `tree` to view folder structure in a tree layout (may need to install) |
