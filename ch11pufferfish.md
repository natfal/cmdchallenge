# PUFFER FISH

## Challenge Text:

```
Delete all of the files in this challenge directory including all subdirectories and their contents.
```
## Solution:

Need to remove all dot files also 

`-r` goes recursively (and also implies `-d` for directories)

`-f` no error / permission errors shown

`*` removes all files - but doesn't include dot files

`.*` includes any file starting with a .

```
$ rm -rf {*,.*}
```