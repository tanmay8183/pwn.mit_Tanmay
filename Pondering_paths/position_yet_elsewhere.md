# Intro To Arguments
We can learn how to navigate and passing the path as an argument using "cd"(changing directories)
## My Solve
**Flag:** 'pwn.college{g12d728T6kOpUGFp8U2xxBBF1aX.QX4QTN0wyMxkjNzEzW}'

first we give the command"/challenge/run" which gives us the directory which we have to use in cd argument to get the flag

```
hacker@paths~position-yet-elsewhere:~$ /challenge/run
Incorrect...
You are not currently in the /usr/share/zoneinfo/posix/Asia directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-yet-elsewhere:~$ cd  /usr/share/zoneinfo/posix/Asia
hacker@paths~position-yet-elsewhere:/usr/share/zoneinfo/posix/Asia$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{g12d728T6kOpUGFp8U2xxBBF1aX.QX4QTN0wyMxkjNzEzW}
```

## What I Learned
I learnt how to navigate and change the directories using "cd"
## References
None.
