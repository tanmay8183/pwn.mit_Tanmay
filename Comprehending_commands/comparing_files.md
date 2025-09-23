# Comparing Files
The challenge asks you to compare two files using "diff" command

## My Solve
**Flag:** ' pwn.college{Uj1KlKKOPr-QEmtf94_14ez8RjG.01MwMDOxwyMxkjNzEzW}'

First we execute the "diff" command with file 1 "/challenge/decoys_only.txt" and "/challenge/decoys_and_real.txt" which compares the data in two files and gives the line which is different from the other in this case the different lines gives us the flag

```
hacker@commands~comparing-files:~$ diff /challenge/decoys_only.txt /challenge/decoys_and_real.txt
45a46
> pwn.college{Uj1KlKKOPr-QEmtf94_14ez8RjG.01MwMDOxwyMxkjNzEzW}
```

## What I Learned
I learnt how to compare two files using "diff" command
## References
None.
