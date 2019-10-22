# Cheat Sheet Vim

## Interact with Unix commands
### run Unix command and display the result
```
:!date
```
### read the stdout of Unix command and put it after the current line
```
:r !date
```
### run current line as bash command and only display the result
```
:.w !bash
```
### run current line as bash command and replace it with result
```
!!bash
```
### run current four lines as stdin of another Unix command and replace them with result
```
4!!sort
```

## @-Functions
To define an @-function:
1. Enter the command(s) you want to execute onto one or more lines of the file you're editing.
2. Yank or delete the line(s) into a named buffer with a command like "ay$ or "bD.
3. To use the function, type a command like @a or @b. You can repeat the function by typing @@ or a dot (.). Use u or U to undo the effects of the @-function.


## Regex
### Get the matched contents stored in hold buffer
Use &, the following command capitalizes every word on a line (\< matches the left word boundary)
```
:s/\<./\u&/g
```
### Compound Searches
Find the first occurence of pattern2 just after pattern1
```
/pattern1/;/pattern2/
```


## Recover backup file
### Recover a file
```
vim -r file
```
### Get a list of files that have backups
```
vim -r
```
