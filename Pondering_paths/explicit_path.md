# Intro To Arguments
The challenge teaches you to explore more explicit relative paths using"." relative paths

## My Solve
**Flag:** 'pwn.college{4nH8Be_01TfhisJrXtAfWH1T0rv.QXwUTN0wyMxkjNzEzW}'

First we execute the "/challenge/run" command which is wrong then we execute "cd /" and then "./challenge/run" and then get the flag

```
hacker@paths~explicit-relative-paths-from-:~$ /challenge/run
Incorrect...
You are not currently in the / directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~explicit-relative-paths-from-:~$ cd /
hacker@paths~explicit-relative-paths-from-:/$ ./challenge/run
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{4nH8Be_01TfhisJrXtAfWH1T0rv.QXwUTN0wyMxkjNzEzW}


```

## What I Learned
I learnt how to use "." command which refers right to the same directory and then running the commands in the directory to get the flag

## References
None.
