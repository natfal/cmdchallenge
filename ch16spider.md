# SPIDER

## Challenge Text:

```
Print all matching lines (without the filename or the file path) in all files under the current directory that start with "access.log" that contain the string "500".

Note that there are no files named access.log in the current directory, you will need to search recursively.
```
## Solution:

```
$ grep -rh --include=\*access.log\* "500"
```
