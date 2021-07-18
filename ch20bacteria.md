# BACTERIA

## Challenge Text:

```
Print the number of lines in access.log that contain the string "GET".
```
## Solution:

```
$ grep "GET" access.log | wc -l
```