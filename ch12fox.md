# FOX

## Challenge Text:

```
There are files in this challenge with different file extensions. Remove all files with the .doc extension recursively in the current working directory.
```
## Solution:

NOTE: works recursively by default

```
$ find -name "*.doc" -delete
```