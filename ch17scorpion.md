# SCORPION

## Challenge Text:

```
Extract all IP addresses from files that start with "access.log" printing one IP address per line.
```
## Solution:

`h` doesn't print file headers\
`o` only part of the lines that match\
`E` the pattern will be extended regex

`[0-9]+\.` at least one digit (but can be more) followed by a decimal point (backslash so it's not the wildcard character)\
`{3}` look for it 3 times exactly\
`[0-9]+` at least one digit

```
$ grep -rhoE --include=\*access.log\* "([0-9]+\.){3}[0-9]+"
```