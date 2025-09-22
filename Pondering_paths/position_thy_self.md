# Intro To Arguments
The challenge changes the directory using changing directory "cd" command

## My Solve
**Flag:** 'pwn.college{AF_BMAmacodCbs_fVx1wJx4xVEa.QX2QTN0wyMxkjNzEzW}'

First we execute "/challenge/run" it then give us the directory we have to use to get the flag using"cd /home"

```
hacker@paths~position-thy-self:~$ /challenge/run
Incorrect...
You are not currently in the /home directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-thy-self:~$ cd /home
hacker@paths~position-thy-self:/home$ challenge/run
bash: challenge/run: No such file or directory
hacker@paths~position-thy-self:/home$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{AF_BMAmacodCbs_fVx1wJx4xVEa.QX2QTN0wyMxkjNzEzW}

```

## What I Learned
I learned how to use cd to change directories and how it does not change the file internally

## References
None.
