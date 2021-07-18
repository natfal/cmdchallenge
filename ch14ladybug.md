# LADYBUG

## Challenge Text:

```
Print all files in the current directory, one per line (not the path, just the filename) that contain the string "500".
```
## Solution:

`r` recursively\
`l` only prints file names - looks for the string in the file and stops once found

```
$ grep -rl "500" *
```