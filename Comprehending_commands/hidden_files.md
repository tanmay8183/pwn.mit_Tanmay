# Hidden Files
The challenge asks you to list out the files which are not in default instead hidden

## My Solve
**Flag:** 'pwn.college{Q93LSRKWPqm9ZP45wRcaXaHAhIb.QXwUDO0wyMxkjNzEzW}'

First we execute the "cd /" command to go into the specified file and then execute "ls-a" to get the hidden files and now in that we have to execute the "cat .flag-28481137071
8704" to get the flag

```
hacker@commands~hidden-files:~$ cd /
hacker@commands~hidden-files:/$ ls -a
.                      challenge  lib64   proc  tmp
..                     dev        libx32  root  usr
.dockerenv             etc        media   run   var
.flag-284811370718704  home       mnt     sbin
bin                    lib        nix     srv
boot                   lib32      opt     sys
hacker@commands~hidden-files:/$ cat .flag-28481137071
8704
pwn.college{Q93LSRKWPqm9ZP45wRcaXaHAhIb.QXwUDO0wyMxkjNzEzW}

```

## What I Learned
I learnt how to list out the hidden files using "ls -a" command which cannot be listed in "ls" command

## References
None.
