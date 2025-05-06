# Vim Commands – Complete Reference Table

This document provides a comprehensive list of Vim commands for quick reference. The table below contains essential commands that will help you work efficiently with Vim.

## Command List

| Command                     | Description                                          |
|-----------------------------|------------------------------------------------------|
| `vim filename.txt`           | Open or create a file                                |
| `:w`                         | Write/save the file                                  |
| `:q`                         | Quit Vim                                             |
| `:wq`                        | Write and quit                                       |
| `ZZ`                         | Write and quit (shortcut)                            |
| `:q!`                        | Quit without saving                                  |
| `:w newfile.txt`             | Save as new file                                     |
| `:waq` or `:wqa`             | Write and quit all tabs                             |
| `:w !sudo tee %`             | Write file as root (without exiting)                 |
| `i`                          | Insert before cursor                                |
| `a`                          | Append after cursor                                 |
| `I`                          | Insert at beginning of line                         |
| `A`                          | Append at end of line                               |
| `o`                          | Open new line below and enter insert mode            |
| `O`                          | Open new line above and enter insert mode            |
| `Esc`                        | Return to normal (command) mode                     |
| `v`                          | Enter visual mode (characterwise)                   |
| `V`                          | Enter visual mode (linewise)                        |
| `h / j / k / l`              | Move left / down / up / right                        |
| `w`                          | Jump to start of next word                          |
| `e`                          | Jump to end of current/next word                    |
| `b`                          | Jump to start of previous word                      |
| `0`                          | Move to beginning of line                           |
| `$`                          | Move to end of line                                 |
| `H / M / L`                  | Move to top / middle / bottom of screen             |
| `:42`                        | Go to line 42                                        |
| `/word`                      | Search for 'word'                                   |
| `n / N`                      | Next / previous search match                        |
| `dd`                         | Delete current line                                 |
| `dw`                         | Delete word from cursor                             |
| `cw`                         | Change (replace) word                               |
| `yy`                         | Copy current line                                   |
| `p`                          | Paste after cursor                                  |
| `P`                          | Paste before cursor                                 |
| `r<char>`                    | Replace single character                            |
| `u`                          | Undo last change                                    |
| `Ctrl + r`                   | Redo undone change                                  |
| `:e filename`                | Open another file                                   |
| `:vsplit file`               | Open file in vertical split                         |
| `Ctrl + w, h/l`              | Switch between splits                               |
| `/pattern`                   | Search forward for the word 'pattern'               |
| `?pattern`                   | Search backward for the word 'pattern'              |
| `n`                          | Repeat the last search in the same direction        |
| `N`                          | Repeat the last search in the opposite direction    |
| `:%s/old/new/g`              | Search and replace 'old' with 'new' throughout the file |
| `:vimgrep /pattern/ *.txt`   | Use grep to search 'pattern' in all .txt files      |
| `yy`                         | Copy (yank) the current line                        |
| `2yy`                        | Copy (yank) 2 lines starting from the current line  |
| `y$`                         | Copy from cursor to end of the line                 |
| `p`                          | Paste content after the cursor                      |
| `P`                          | Paste content before the cursor                     |
| `dd`                         | Cut (delete) the current line                       |
| `2dd`                        | Cut (delete) 2 lines starting from the current line |
| `D`                          | Cut (delete) from cursor to end of the line         |
| `x`                          | Cut (delete) the character under the cursor         |
| `:w`                         | Write (save) the file without exiting               |
| `:w !sudo tee %`             | Write file as root without exiting (useful if forgot sudo) |
| `:wq`                        | Write and quit                                       |
| `:q`                         | Quit Vim                                             |
| `:q!`                        | Force quit without saving changes                    |
| `:wqa`                       | Save and quit all active tabs (buffers)              |
