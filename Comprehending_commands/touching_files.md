# Touching Files
The challenge asks you to create file using "touch" command

## My Solve
**Flag:** 'pwn.college{URa1VGUkw4kKcdb0e0ZI49DHcQg.QXwMDO0wyMxkjNzEzW}'

First we execute the "cd /tmp" command to change to tmp directory and then we use the "touch" command to input both college and pwn file and after that we execute the "/challenge/run" command to get the flag

```
hacker@commands~touching-files:~$ cd /tmp
hacker@commands~touching-files:/tmp$ touch pwn
hacker@commands~touching-files:/tmp$ ls
bin  hsperfdata_root  pwn  tmp.TpSOPGOVKK
hacker@commands~touching-files:/tmp$ touch college
hacker@commands~touching-files:/tmp$ ls
bin  college  hsperfdata_root  pwn  tmp.TpSOPGOVKK
hacker@commands~touching-files:/tmp$ /challenge/run
Success! Here is your flag:
pwn.college{URa1VGUkw4kKcdb0e0ZI49DHcQg.QXwMDO0wyMxkjNzEzW}
```

## What I Learned
I learnt how to create file using "touch" command

## References
None.
