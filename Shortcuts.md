# Vim Shortcuts

## Movement options
`b` - move cursor by word (to back) <br>
`w` - move cursor by word (to front) <br>
`W` - move cursor by space (forward) <br>
`B` - move cursor by space (back) <br>
`{` - move cursor blockwise (to back)<br>
`}` - move cursor blockwise (to front)<br>
`0 + w` - move cursor to firstmost character in the line <br>
`ctrl` + `e` - scroll down<br>
`ctrl` + `y` - scroll up<br>
`ctrl` + `d` - move cursor to next page<br>
`ctrl` + `u` - move cursor to previos page<br>
`gg` - top of the page<br>
`G` - bottom of the page<br>
### Cursor options
`f` + `"any character"` - works like a goto (goes to the first occurence of that character im the line) <br>
`f` + `"any character" + ;` - go to next instance of the char in the line<br>
`%` - moves to the matching parenthesis occurence<br>
`*` - shows all the occurences of that word in the code<br>
`A` - goes to end of the line and insert mode (useful for commenting)<br>
`I` - goes to beginning of the line and insert mode<br>

## Location options
`ctrl` + `i` - jump up a location<br>
`ctrl` + `o` - jump down a location<br>
`''` - go to previous location (where cursor has been)<br>

## Delete options
`d` +` %` - delete everything contained inside that parenthesis<br>
`C` - delete whatever is after the cursor and enters insert mode<br>
`D` - deletes whatever is on the right of the cursor<br>
`d` + `t` + `"any charayter"` - deletes right portion until the said char<br>
## Text options
`~` - switch lower case or uppercase of the char<br>
`.` - executes the previous command executed (useful for combination commands) <br>


## Page options
`/` - find in page<br>
`n` - next item in find<br>
`N` - previous item in find<br>
