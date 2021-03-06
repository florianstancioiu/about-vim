# Learning VIM

Here is a list of commands I learned while coding with VIM

These are the commands I find most useful

### Enter write mode

`:i`

### Exit write mode

`esc`

### Write file to disk

`:w`

### Close file

`:q`

### Force the command

`:!`, `:wq!` - to force writting the file and closing vim

### Exit vim

`:exit`


### Enter visual mode (useful for copy and paste)

`:v`

### Copy lines (while in visual mode)

`y`

### Cut lines (while in visual mode)

`c`

### Paste lines 

`p`

### Double (copy and paste) the current line

`yy` and `p`

### Delete the current line

`dd`

### Indent to the right (it also works with the visual mode)

`>>`

### Indent to the left (it also works with the visual mode)

`<<`

### Explore the current directory

`:E` or `:Explore`

### Open a new tab in directory explore mode

`:Te`

### Open a new tab

`:tabnew`

### Move to the next tab

`:tabn`

### Move to the previous tab

`:tabp`

### Cycle forward through tabs using keys

`g` + `t`

### Cycle backwards through tabs using keys

`g` + `T`

### Go back to the previous buffer (useful to get back to directory mode after closing a file)

`ctrl` + `o`

### Search a string

`:/string-to-search`

### Go to the next occurence of the searched string

`n`

### Go to the previous occurence of the searched string

`N`

### Search and replace a string with another string

`:%s/string/another-string/g`

### Create horizontal split screen 

`:sp` or `ctrl` + `w` + `s`

### Create vertical split screen

`:vsp` or `ctrl` + `w` + `v` 

### Change between split screens

`ctrl` + `w` + `w`
