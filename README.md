Hi, MY NAME IS JANIS
I'm new to github and trying to learn it
date - 01-06-24

STUDENT@DESKTOP-S0EL170 MINGW64 ~/JANIS (main)
$ cd ..

STUDENT@DESKTOP-S0EL170 MINGW64 ~ (main)
$ cd jniss
bash: cd: jniss: No such file or directory

STUDENT@DESKTOP-S0EL170 MINGW64 ~ (main)
$ cd janiss

STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss (main)
$ cd desktop-tutorial
janis is cool

STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss/desktop-tutorial (main)
$ git clone https://github.com/janisAnup/desktop-tutorial.git
Cloning into 'desktop-tutorial'...
remote: Enumerating objects: 95, done.
remote: Counting objects: 100% (95/95), done.
remote: Compressing objects: 100% (53/53), done.
remote: Total 95 (delta 19), reused 86 (delta 10), pack-reused 0 (from 0)
Receiving objects: 100% (95/95), 20.65 KiB | 2.29 MiB/s, done.
Resolving deltas: 100% (19/19), done.

STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss/desktop-tutorial (main)
$ ls
desktop-tutorial/  my-proj/  README.md

STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss/desktop-tutorial (main)
$ touch about.txt

STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss/desktop-tutorial (main)
$ ls
about.txt  desktop-tutorial/  my-proj/  README.md

STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss/desktop-tutorial (main)
$ vim about.txt

STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss/desktop-tutorial (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.txt
        desktop-tutorial/

nothing added to commit but untracked files present (use "git add" to track)

STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss/desktop-tutorial (main)
$ git add about.txt
warning: in the working copy of 'about.txt', LF will be replaced by CRLF the next time Git touches it

STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss/desktop-tutorial (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        desktop-tutorial/


STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss/desktop-tutorial (main)
$ git commit -m "about.txt is added"
[main 7a3d0a9] about.txt is added
 1 file changed, 1 insertion(+)
 create mode 100644 about.txt

STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss/desktop-tutorial (main)
$  git push origin main
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/janisAnup/desktop-tutorial.git
   768200e..7a3d0a9  main -> main

STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss/desktop-tutorial (main)
$

STUDENT@DESKTOP-S0EL170 MINGW64 ~/janiss/desktop-tutorial (main)
$
