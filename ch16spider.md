# SPIDER

## Challenge Text:

```
Print all matching lines (without the filename or the file path) in all files under the current directory that start with "access.log" that contain the string "500".

Note that there are no files named access.log in the current directory, you will need to search recursively.
```
## Solution:

`h` don't print filename headers

`--include==pattern` only files matching the pattern are searched (matched to full path file)

```
$ grep -rh --include=\*access.log\* "500"
```
