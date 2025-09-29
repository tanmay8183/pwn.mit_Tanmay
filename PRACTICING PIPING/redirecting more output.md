# Redirecting More Output
The challenge asks you to redirect more outputs

## My Solve
**Flag:** 'pwn.college{odufXm5hsqMZcWK6poQlE-oRbBD.QX1YTN0wyMxkjNzEzW}'

First we execute the '/challenge/run > myflag' which redirects into myflag and then we execute 'cat myflag' to getv the flag

```
hacker@piping~redirecting-more-output:~$ /challenge/run > myflag
[INFO] WELCOME! This challenge makes the following asks of you:
[INFO] - the challenge will check that output is redirected to a specific file path : myflag
[INFO] - the challenge will output a reward file if all the tests pass : /flag

[HYPE] ONWARDS TO GREATNESS!

[INFO] This challenge will perform a bunch of checks.
[INFO] If you pass these checks, you will receive the /flag file.

[TEST] You should have redirected my stdout to a file called myflag. Checking...

[PASS] The file at the other end of my stdout looks okay!
[PASS] Success! You have satisfied all execution requirements.
hacker@piping~redirecting-more-output:~$ cat myflag

[FLAG] Here is your flag:
[FLAG] pwn.college{odufXm5hsqMZcWK6poQlE-oRbBD.QX1YTN0wyMxkjNzEzW}
```

## What I Learned
I learnt how to redirect multiple outputs
## References
None.
