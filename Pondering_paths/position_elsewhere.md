# Intro To Arguments
The challenge asks you to change the absolute path using "cd"
## My Solve
**Flag:** 'pwn.college{QpZY4-gGGRZiksR_RiNt6h2AP3C.QX3QTN0wyMxkjNzEzW}'

We first give the command"/challenge/run" which then gives the specific path which we should use to get the flag

```
hacker@paths~position-elsewhere:~$ /challenge/run
Incorrect...
You are not currently in the /usr/share/doc directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-elsewhere:~$ cd /usr/share/doc
hacker@paths~position-elsewhere:/usr/share/doc$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{QpZY4-gGGRZiksR_RiNt6h2AP3C.QX3QTN0wyMxkjNzEzW}

```

## What I Learned
I learnt how to change the directory using cd to a specific directory 
## References
None.
