# SCORPION

## Challenge Text:

```
Extract all IP addresses from files that start with "access.log" printing one IP address per line.
```
## Solution:

`h` doesn't print file headers
`o` only part of the lines that match
`E` the pattern will be extended regex
`\d` a digit
`.` a literal . character (don't use backslash for it, otherwise it will think it is the wildcard)
`{,3}` means at most 3 instances of the previous letter

```
$ grep -rhoE --include=\*access.log\* "\d{,3}.\d{,3}.\d{,3}.\d{,3}"
```