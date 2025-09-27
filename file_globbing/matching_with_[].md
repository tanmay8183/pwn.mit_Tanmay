# Matching With []
The challenge asks you to use [] command to get the flag

## My Solve
**Flag:** 'pwn.college{IjNWAgdKVvhZCk6fWMXGb5vexzO.QXzIDO0wyMxkjNzEzW}'

First we execute the "cd/c*/f*" command to change directory and then we run "/challenge/run" with "file_[absh]" as argument to get the flag

```
hacker@globbing~matching-with-:~$ cd /c*/f*
hacker@globbing~matching-with-:/challenge/files$ /challenge/run file_[absh]
You got it! Here is your flag!
pwn.college{IjNWAgdKVvhZCk6fWMXGb5vexzO.QXzIDO0wyMxkjNzEzW}
```

## What I Learned
I learnt how Linux commands can take up "[]" to get require the particular files from the set of files

## References
None.
