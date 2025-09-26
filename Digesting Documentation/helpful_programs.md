# Helpful Programs
The challenge asks you to use the "--help" command to get the help and solve

## My Solve
**Flag:** 'pwn.college{4cjReCE2bKnqTIiKmJNjFjwHIei.QX3IDO0wyMxkjNzEzW}'

First we execute the "--help" command to get the commands to use to get the flag in this case the "-p" is given to get the secret code and then use the "-g" to get the flag

```
hacker@man~helpful-programs:~$ /challenge/challenge --help
^[[Dusage: a challenge to make you ask for help [-h] [--fortune] [-v]
                                            [-g GIVE_THE_FLAG] [-p]

optional arguments:
  -h, --help            show this help message and exit
  --fortune             read your fortune
  -v, --version         get the version number
  -g GIVE_THE_FLAG, --give-the-flag GIVE_THE_FLAG
                        get the flag, if given the correct value
  -p, --print-value     print the value that will cause the -g option
                        to give you the flag
hacker@man~helpful-programs:~$ /challenge/challenge -p
The secret value is: 423
hacker@man~helpful-programs:~$ /challenge/challenge -g 423
Correct usage! Your flag: pwn.college{4cjReCE2bKnqTIiKmJNjFjwHIei.QX3IDO0wyMxkjNzEzW}
```

## What I Learned
I learnt how to use the "help" command to get to know the further steps to solve

## References
None.
