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
