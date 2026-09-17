Table of contents

1.[Watch command in linux](#watch-command-linux)
1.[tail/head command in linux](#tail/head-command-linux)
1.[grep command in linux](#grep-command-in-linux)

## watch-command-linux
Watch command in linux can be used to keep running the same command for every particulat second instead of re running the command manually. 

eg:
```
watch -n 1 {{command}}
-n 1 -> stands for seconds
```

## tail/head-command-linux
The tail / head command in linux can be used to read the contents of the file.  The head command is used to read from the start.  And the tail command is used to read the bottom of the file. 

Note:  We can also -n to specify the number of that we want to read.

## grep-command-in-linux
grep is used to search for a specific text or pattern inside files or command output.

eg:
```
grep [options] "pattern" file
```

| Option | Definition |
|--------|------------|
| `-i` | Ignore uppercase/lowercase differences |
| `-r` | Search recursively inside directories |
| `-n` | Show the line number of each match |
| `-v` | Show lines that do not match |
| `-w` | Match the complete word only|
