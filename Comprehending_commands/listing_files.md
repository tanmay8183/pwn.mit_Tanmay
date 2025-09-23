# Intro To Arguments
The challenge asks you to list out the files under a given directory
## My Solve
**Flag:** 'pwn.college{cvixzJ1M3Kqng9MnTBBEalBugyX.QX4IDO0wyMxkjNzEzW}'

First we execute the 'ls' command followed by "/challenge" to give out the files under which we should execute. After we executed the first command it gives you the file which is renamed and now we can use that to get the flag using "/challenge/7780-renamed-run-29942"

```
hacker@commands~listing-files:~$ ls /challenge
7780-renamed-run-29942  DESCRIPTION.md
hacker@commands~listing-files:~$ /challenge/7780-renamed-run-29942
Yahaha, you found me! Here is your flag:
pwn.college{cvixzJ1M3Kqng9MnTBBEalBugyX.QX4IDO0wyMxkjNzEzW}
```

## What I Learned
I learnt how to list the files under a particular directory using "ls" command

## References
None.
