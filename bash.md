# Cheat Sheet Bash

## Extended Globbing
### enable
shopt -s extglob
### disable
shopt -u extglob
### operators
The full available extended globbing operators are (excerpt
from man bash):

    If the extglob shell option is enabled using the shopt
    builtin, several extended pattern matching operators are
    recognized.A pattern-list is a list of one or more
    patterns separated by a |. Composite patterns may be
    formed using one or more of the following sub-patterns:
   
      □ ?(pattern-list)
        Matches zero or one occurrence of the given patterns
      □ *(pattern-list)
        Matches zero or more occurrences of the given patterns
      □ +(pattern-list)
        Matches one or more occurrences of the given patterns
      □ @(pattern-list)
        Matches one of the given patterns
      □ !(pattern-list)
        Matches anything except one of the given patterns

So, for example, if you wanted to list all the files in the
current directory that are not .c or .h files, you would do:

$ ls -d !(*@(.c|.h))

Of course, normal shell globing works, so the last example
could also be written as:

$ ls -d !(*.[ch])

