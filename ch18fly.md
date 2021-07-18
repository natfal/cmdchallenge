# FLY

## Challenge Text:

```
Count the number of files in the current working directory. Print the number of files as a single integer.
```
## Solution:

`ls -l` list all file names, one on each line\
`wc -l` count how many lines the input has (by piping in ls -l, get number of files)

```
$ ls -l | wc -l
```