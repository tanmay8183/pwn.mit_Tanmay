# Searching For Manuals
The challenge asks you to man man with another man command to get the argument

## My Solve
**Flag:** ' pwn.college{oiYqPsgcpcPwrzMFV-haEB9jKFB.QX2EDO0wyMxkjNzEzW}'

First we execute the "man man" command to get the manual and also search for the argument in the manual to use it as the argument to get the manual in which the challenge argument is present to get the flag.

```
hacker@man~searching-for-manuals:~$ man man
hacker@man~searching-for-manuals:~$ man -k challenge
oiqsgcpcwr (1)       - print the flag!
hacker@man~searching-for-manuals:~$ man oiqsgcpcwr
hacker@man~searching-for-manuals:~$ /challenge/challenge   --oiqsgc 920
Correct usage! Your flag: pwn.college{oiYqPsgcpcPwrzMFV-haEB9jKFB.QX2EDO0wyMxkjNzEzW}
```

## What I Learned
I learnt how to use man again and again to get the flag

## References
None.
