#knowledge
#linux
#commandLine

# How to find a human readable string preceded by a specific pattern in a file using the command line?

```sh
$ strings path/to/file | grep -E "<pattern>"
```

- `strings path/to/file`: Prints all strings in a binary.
- `grep -E <pattern>`: Searches for a pattern.
