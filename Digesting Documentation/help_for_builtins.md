# Help For Builtins
The challenge asks you to take the help of help command

## My Solve
**Flag:** 'pwn.college{skOtILe_oE3Oz3kePbg9ViXFjLV.QX0ETO0wyMxkjNzEzW}'

First we execute the "help challenge" command to seek for trhe help of further steps then we use the given secret code in the given syntax to get the flag
```
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "skOtILe_".
hacker@man~help-for-builtins:~$ challenge --secret skOtILe_
Correct! Here is your flag!
pwn.college{skOtILe_oE3Oz3kePbg9ViXFjLV.QX0ETO0wyMxkjNzEzW}
```

## What I Learned
I learnt how to make use of the "help" command to get datas
## References
None.
