# Matching With "*"
The challenge asks you to use the "*"command to get the flag

## My Solve
**Flag:** 'pwn.college{IyDj8g9X391eQxn739jZGoFjLyH.QXxIDO0wyMxkjNzEzW}
'
First we execute the "cds /c*" command because the * will open the directory which starts with "c" and then we execute the "/challenge/run" to get the flag

```
hacker@globbing~matching-with-:~$ cd /c*
hacker@globbing~matching-with-:/challenge$ /challenge/run
You ran me with the working directory of /challenge! Here is your flag:
pwn.college{IyDj8g9X391eQxn739jZGoFjLyH.QXxIDO0wyMxkjNzEzW}
```

## What I Learned
I learnt how to search for any file or directory using "*" command

## References
None.
