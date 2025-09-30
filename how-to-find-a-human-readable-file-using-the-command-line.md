#knowledge
#linux
#commandLine

# How to find a human readable file using the command line?

```sh
$find /dir/to/search -type f | xargs file | grep ASCII
```

`find /dir/to/search -type f` will find normal files (no directories or links).
`xargs file` will run the file command on each of the files and tell what kind of file it is.
`grep ASCII` will return only the results that contains ASCII on it.