# STRIPED FISH

## Challenge Text:

```
A symbolic link is a type of file that is a reference to another file.

Create a symbolic link named take-the-command-challenge that points to the file tmp/files/take-the-command-challenge.
```
## Solution:

`ln` create a link

`s` make it symbolic

NOTE: the location of the file goes first, followed by the link name

```
$ ln -s tmp/files/take-the-command-challenge take-the-command-challenge
```