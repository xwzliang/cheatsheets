# Cheat Sheet Git

## Remote URL
### View Remote URL
git remote -v
### Changing a Git Remote's URL
git remote set-url origin git@gitserver.com:user/repo_name.git

## Log
### Retrieve the commit log for a specific line in a file
git log -L 155,155:file.sh

This means "trace the evolution of lines 155 to 155 in the file named file.sh".