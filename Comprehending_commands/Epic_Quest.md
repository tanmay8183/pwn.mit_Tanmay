# Intro To Arguments
The challenge asks you to use "ld","cat","vd" command again and again
## My Solve
**Flag:** 'pwn.college{gjBlbbREeeyPEosrqWqOAJp18tC.QX5IDO0wyMxkjNzEzW}'

First we execute the "cd" and then "ls" and also "cat" again and again because we get the hint at each level and at the end we get the flag
```
hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ ls
INFO  boot       dev  flag  lib    lib64   media  nix  proc  run   srv  tmp  var
bin   challenge  etc  home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~an-epic-filesystem-quest:/$ cat INFO
Tubular find!
The next clue is in: /usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/$ cd /usr/local/lib/python3.8/dist-packages/ju
pyter_server/services/api/__pycache__
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__$ ls
MEMO  __init__.cpython-38.pyc  handlers.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__$ cat MEMO
Great sleuthing!
The next clue is in: /usr/share/locale/pl/LC_MESSAGES

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__$ ls -a /usr/share/locale/pl/LC_MESSAGES
.         dpkg.mo        iso_3166-2.mo  iso_4217.mo   iso_639.mo        sphinx.mo
..        fish.mo        iso_3166-3.mo  iso_639-2.mo  iso_639_3.mo
.INSIGHT  iso_15924.mo   iso_3166.mo    iso_639-3.mo  iso_639_5.mo
apt.mo    iso_3166-1.mo  iso_3166_2.mo  iso_639-5.mo  libapt-pkg6.0.mo
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__$ cat /usr/share/locale/pl/LC_MESSAGES/INSIGHTT
cat: /usr/share/locale/pl/LC_MESSAGES/INSIGHTT: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__$ cat /usr/share/locale/pl/LC_MESSAGES/INSIGHT
cat: /usr/share/locale/pl/LC_MESSAGES/INSIGHT: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__$ cat INSIGHT
cat: INSIGHT: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__$ cat /usr/share/locale/pl/LC_MESSAGES/.INSIGHT
Great sleuthing!
The next clue is in: /usr/local/lib/python3.8/dist-packages/cryptography/hazmat/backends/openssl

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__$ ls /usr/local/lib/python3.8/dist-packages/cryptography/hazmat/backends/openssl
HINT-TRAPPED  __init__.py  __pycache__  backend.py
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__$ cat /usr/local/lib/python3.8/dist-packages/cryptography/hazmat/backends/openssl/HINT-TRAPPED
Great sleuthing!
The next clue is in: /opt/linux/linux-5.4/drivers/staging/greybus/Documentation
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__$ ls  /opt/linux/linux-5.4/drivers/staging/greybus/Documentation
POINTER  firmware  sysfs-bus-greybus
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__$ cat  /opt/linux/linux-5.4/drivers/staging/greybus/Documentation/POINTER
Congratulations, you found the clue!
The next clue is in: /usr/share/icons/hicolor/16x16/apps

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/jupyter_server/services/api/__pycache__$ cd /usr/share/icons/hicolor/16x16/apps
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/hicolor/16x16/apps$ ls
CLUE  emacs.png  firefox.png  openjdk-11.png  openjdk-17.png  xcas.png
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/hicolor/16x16/apps$ cat CLUE
Great sleuthing!
The next clue is in: /usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/STIX-Web/Size3

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/hicolor/16x16/apps$ ls -a /usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/STIX-Web/Size3
.  ..  .NUGGET  Regular
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/hicolor/16x16/apps$ ls -a /usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/STIX-Web/Size3/.NUGGET
/usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/STIX-Web/Size3/.NUGGET
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/hicolor/16x16/apps$ cat /usr/s
hare/javascript/mathjax/jax/output/HTML-CSS/fonts/STIX-Web/Size3/.NUGGET
Yahaha, you found me!
The next clue is in: /opt/pt-dump/.git/info
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/hicolor/16x16/apps$ ls /opt/pt-dump/.git/info
GIST  exclude
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/hicolor/16x16/apps$ cat /opt/pt-dump/.git/info/GIST
Congratulations, you found the clue!
The next clue is in: /opt/linux/linux-5.4/drivers/soc/bcm

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/hicolor/16x16/apps$ cd /opt/li/linux-5.4/drivers/soc/bcm
bash: cd: /opt/li/linux-5.4/drivers/soc/bcm: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/share/icons/hicolor/16x16/apps$ cd /opt/linux/linux-5.4/drivers/soc/bcm
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/soc/bcm$ ls
Kconfig   REVELATION       brcmstb     raspberrypi-power.c
Makefile  bcm2835-power.c  built-in.a
hacker@commands~an-epic-filesystem-quest:/opt/linux/linux-5.4/drivers/soc/bcm$ cat REVELATION
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{gjBlbbREeeyPEosrqWqOAJp18tC.QX5IDO0wyMxkjNzEzW}
```

## What I Learned
I learnt how to use cat,cd,ls,ls-a alltogether in one code

## References
None.
