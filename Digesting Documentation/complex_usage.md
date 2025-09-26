# Complex Usage
The challenge asks you to get the flag using complex arguments with documentations

**Flag:** 'pwn.college{w5UgNxH-_0NTRC2IiCgOAwj8ugi.QX1ITO0wyMxkjNzEzW}'

First we execute the la command to get the challenge directory and then we use the documentation command to get the flag

```
hacker@man~learning-complex-usage:~$ ls
 Desktop   Downloads  '~'
hacker@man~learning-complex-usage:~$ ls /challenge/challenge
/challenge/challenge
hacker@man~learning-complex-usage:~$ ls /challenge/
DESCRIPTION.md  challenge
hacker@man~learning-complex-usage:~$ find / -name flag
find: ‘/root’: Permission denied
find: ‘/proc/1/task/1/fd’: Permission denied
find: ‘/proc/1/task/1/fdinfo’: Permission denied
find: ‘/proc/1/task/1/ns’: Permission denied
find: ‘/proc/1/fd’: Permission denied
find: ‘/proc/1/map_files’: Permission denied
find: ‘/proc/1/fdinfo’: Permission denied
find: ‘/proc/1/ns’: Permission denied
find: ‘/proc/7/task/7/fd’: Permission denied
find: ‘/proc/7/task/7/fdinfo’: Permission denied
find: ‘/proc/7/task/7/ns’: Permission denied
find: ‘/proc/7/fd’: Permission denied
find: ‘/proc/7/map_files’: Permission denied
find: ‘/proc/7/fdinfo’: Permission denied
find: ‘/proc/7/ns’: Permission denied
find: ‘/var/log/private’: Permission denied
find: ‘/var/log/apache2’: Permission denied
find: ‘/var/log/mysql’: Permission denied
find: ‘/var/cache/ldconfig’: Permission denied
find: ‘/var/cache/apt/archives/partial’: Permission denied
find: ‘/var/cache/private’: Permission denied
find: ‘/var/lib/apt/lists/partial’: Permission denied
find: ‘/var/lib/php/sessions’: Permission denied
find: ‘/var/lib/mysql-files’: Permission denied
find: ‘/var/lib/private’: Permission denied
find: ‘/var/lib/mysql-keyring’: Permission denied
find: ‘/var/lib/mysql’: Permission denied
find: ‘/tmp/tmp.TpSOPGOVKK’: Permission denied
find: ‘/run/mysqld’: Permission denied
find: ‘/run/sudo’: Permission denied
find: ‘/etc/ssl/private’: Permission denied
/usr/local/lib/python3.8/dist-packages/pwnlib/flag
/opt/pwndbg/.venv/lib/python3.8/site-packages/pwnlib/flag
/flag
/nix/store/7ns27apnvn4qj4q5c82x0z1lzixrz47p-radare2-5.9.8/share/radare2/5.9.8/flag
/nix/store/5z3sjp9r463i3siif58hq5wj5jmy5m98-python3.12-pwntools-4.13.1/lib/python3.12/site-packages/pwnlib/flag
/nix/store/5n5lp1m8gilgrsriv1f2z0jdjk50ypcn-rizin-0.7.3/share/rizin/flag
/nix/store/bnlabj2vsbljhp597ir29l51nrqhm89w-rizin-0.7.4/share/rizin/flag
/nix/store/s8b49lb0pqwvw0c6kgjbxdwxcv2bp0x4-radare2-5.9.8/share/radare2/5.9.8/flag
/nix/store/1hyxipvwpdpcxw90l5pq1nvd6s6jdi5m-python3.12-pwntools-4.14.1/lib/python3.12/site-packages/pwnlib/flag
/nix/store/h88mxp2mbgyj06vypwmqpy05idhwimnp-python3.13-pwntools-4.14.1/lib/python3.13/site-packages/pwnlib/flag
/nix/store/5qz6hgb1qzpvjrsw20wyiylx5zw8b9bk-pwntools-4.14.0/lib/python3.13/site-packages/pwnlib/flag
hacker@man~learning-complex-usage:~$ /challenge/challenge  --printfile /usr/local/lib/python3.8/dist-packages/pwnlib/flag
Correct argument! Here is the /usr/local/lib/python3.8/dist-packages/pwnlib/flag file:
cat: /usr/local/lib/python3.8/dist-packages/pwnlib/flag: Is a directory
hacker@man~learning-complex-usage:~$ cat  /usr/local/lib/python3.8/dist-packages/pwnlib/flag
cat: /usr/local/lib/python3.8/dist-packages/pwnlib/flag: Is a directory
hacker@man~learning-complex-usage:~$ /challenge/challenge  --printfile /usr/l
Correct argument! Here is the /usr/l file:
cat: /usr/l: No such file or directory
hacker@man~learning-complex-usage:~$ /challenge/challenge  --printfile /flag
Correct argument! Here is the /flag file:
pwn.college{w5UgNxH-_0NTRC2IiCgOAwj8ugi.QX1ITO0wyMxkjNzEzW}
```

## What I Learned
I learnt how to use documentation with complex commands
## References
None.
