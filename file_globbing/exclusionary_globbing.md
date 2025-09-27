# Exclusionary Globbing
The challenge asks you to filter out files using [!] command

## My Solve
**Flag:** 'pwn.college{wowF1L1wd49rlvkRn3JcOrdFpLa.QX2IDO0wyMxkjNzEzW}'

First we execute the cd command to change directory and then " /challenge/run [!pwn]*" to get the flag

```
hacker@globbing~exclusionary-globbing:~$ cd /c*/f*
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [!pwn]*
You got it! Here is your flag!
pwn.college{wowF1L1wd49rlvkRn3JcOrdFpLa.QX2IDO0wyMxkjNzEzW}

```

## What I Learned
I learnt how to use [!] to filter out files and get the flag

## References
None.
