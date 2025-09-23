# Removing Files
The challenge asks you to remove the files using "rm" command

## My Solve
**Flag:** 'pwn.college{A3GhokJ9JupkepJFz92hPkFIl0I.QX2kDM1wyMxkjNzEzW}'

First we execute the "touch delete_me" command to create a file and then we use "ls" to list the files out and check if the file exists and then we use "rm delete _me"to remove the file and then we give the "/challenge/run" command to get the flag

```
hacker@commands~removing-files:~$ touch delete_me
hacker@commands~removing-files:~$ ls
 Desktop   Downloads   delete_me  '~'
hacker@commands~removing-files:~$ rm delete_me
hacker@commands~removing-files:~$ /challenge/check
Excellent removal. Here is your reward:
pwn.college{A3GhokJ9JupkepJFz92hPkFIl0I.QX2kDM1wyMxkjNzEzW}
```

## What I Learned
I learnt how to remove files using "rm" command when there are useless files 
## References
None.
