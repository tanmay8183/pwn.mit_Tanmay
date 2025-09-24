# Making Directory
This challenges asks you to make directories using "mkdir" command

## My Solve
**Flag:** 'pwn.college{QN4gYJ6KU-1ieyf1rCsdHdh2jfN.QXxMDO0wyMxkjNzEzW}'

First we execute the "cd tmp" command to change the directory and then we execute the "mkdir pwn" command and then finally we use the "touch college" command to add the file and now "/challenge/run" will give you the flag
```
hacker@commands~making-directories:~$ cd tmp
bash: cd: tmp: No such file or directory
hacker@commands~making-directories:~$ cd /tmp
hacker@commands~making-directories:/tmp$ mkdir pwn
hacker@commands~making-directories:/tmp$ cd pwn
hacker@commands~making-directories:/tmp/pwn$ touch college
hacker@commands~making-directories:/tmp/pwn$ ls
college
hacker@commands~making-directories:/tmp/pwn$ /challenge/run
Success! Here is your flag:
pwn.college{QN4gYJ6KU-1ieyf1rCsdHdh2jfN.QXxMDO0wyMxkjNzEzW}
```

## What I Learned
I learnt how to create directories using "mkdir" command to in desired location 

## References
None.
