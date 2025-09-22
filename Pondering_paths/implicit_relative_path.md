# Intro To Arguments
The challenge is to find the directory on our own using "cd" and create working directories

## My Solve
**Flag:** 'pwn.college{4tdwXx_I-h51XRdD2sH_RXdozLh.QX5QTN0wyMxkjNzEzW}'

First we execute the 'challenge/run" which will not tell the directory and we have to find out in this case it is inside "/challenge/run"

```
hacker@paths~implicit-relative-paths-from-:~$ /challenge/run
Incorrect...
You are not currently in the / directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~implicit-relative-paths-from-:/$ cd /challenge
hacker@paths~implicit-relative-paths-from-:/challenge$ cd /
hacker@paths~implicit-relative-paths-from-:/$ challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{4tdwXx_I-h51XRdD2sH_RXdozLh.QX5QTN0wyMxkjNzEzW}
```

## What I Learned
I learnt how to navigate through directories and get the flag

## References
None.
