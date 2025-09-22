# Intro To Arguments
Using of "~/~" command 

## My Solve
**Flag:** 'pwn.college{cGjyvHTQlWLIinMVY6chbTVxIKv.QXzMDO0wyMxkjNzEzW}'

First we execute the "/challenge/run ~/~" which will write the file to /home/hacker/~ and reads the flag

```
hacker@paths~home-sweet-home:~$ /challenge/run ~/~
Writing the file to /home/hacker/~!
... and reading it back to you:
pwn.college{cGjyvHTQlWLIinMVY6chbTVxIKv.QXzMDO0wyMxkjNzEzW
```

## What I Learned
I learnt that "~" is the current working directory with it being the short form of "/home/hacker/"

## References
None.
