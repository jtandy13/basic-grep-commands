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
```

## Search the current directory for a string pattern
```bash
grep "string to look for" *
```

## Recursively search the current directory for a string pattern
```bash
grep -R "string to look for" *
```

## Case insensitive search
```bash
grep -i "StInG To LoOk FoR"
```
