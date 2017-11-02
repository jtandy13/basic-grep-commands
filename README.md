# basic-grep-commands
A collection of commonly used grep commands

## Syntax
```
-i case insensitive
-r recursive search
-w whole words only
-A<num> include trailing text
-B<num> include leading text
-C<num> include trailing and leading text
-H print the file name with each match
-l return only file names
-c returns the file name and the number of hits
```

## Search the current directory for a string pattern
```bash
grep "string to look for" *
```

## Recursively search the current directory for a string pattern
```bash
grep -r "string to look for" *
```

## Return all files that contain the keyword in current directory and sub-directories
```bash
grep -lr "string to look for" *
```
