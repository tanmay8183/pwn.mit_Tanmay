# Multiple options for tab completion
The challenge asks you how to use tab for multiple options of files

## My Solve
**Flag:** 'pwn.college{M2BKDDaOzaQwkEcG85uTCvafKkl.0lN0EzNxwyMxkjNzEzW}'

First we execute the "/challenge/files/pwn" then "cat /challenge/files/pwncollege-flag" to get the flag

```
hacker@globbing~multiple-options-for-tab-completion:~$ /challenge/files/pwn
pwn                    pwncollege-flamingo
pwn-college            pwncollege-flyswatter
pwn-the-planet         pwncollege-hacking
pwncollege-family
hacker@globbing~multiple-options-for-tab-completion:~$ cat /challenge/files/pwncollege-flag
pwn.college{M2BKDDaOzaQwkEcG85uTCvafKkl.0lN0EzNxwyMxkjNzEzW}

```

## What I Learned
I learnt how Linux commands allows you to use tab for multiple files using tab command

## References
None.
