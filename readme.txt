
jstin@DESKTOP-0J7J0RJ MINGW64 ~
$ cd it120_sample

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample
$ git init
Initialized empty Git repository in C:/Users/jstin/it120_sample/.git/

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ touch profile.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ touch education.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ touch background.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ touch readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ touch test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ notedpad profile.txt
bash: notedpad: command not found

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ add .
bash: add: command not found

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ notepad profile.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ notepad education.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ notepad background.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ notepad text.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ notedpad test.py
bash: notedpad: command not found

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ ls
background.txt  education.txt  profile.txt  readme.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ notepad test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git remove readme.txt
git: 'remove' is not a git command. See 'git --help'.

The most similar command is
        remote

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ ls
background.txt  education.txt  profile.txt  readme.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git rm readme.txt
error: the following file has changes staged in the index:
    readme.txt
(use --cached to keep the file, or -f to force removal)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git rm --cached readme.txt
rm 'readme.txt'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ ls
background.txt  education.txt  profile.txt  readme.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git rm readme.txt
fatal: pathspec 'readme.txt' did not match any files

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ ls
background.txt  education.txt  profile.txt  readme.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git reset HEAD readme.txt
fatal: ambiguous argument 'HEAD': unknown revision or path not in the
ee.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ ls
background.txt  education.txt  profile.txt  readme.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ ^C

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git commit -m "Save"
[main (root-commit) 32468b2] Save
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 background.txt
 create mode 100644 education.txt
 create mode 100644 profile.txt
 create mode 100644 test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory
        modified:   background.txt
        modified:   education.txt
        modified:   profile.txt
        modified:   test.py

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.txt

no changes added to commit (use "git add" and/or "git commit -a")

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git commit -m "save"
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory
        modified:   background.txt
        modified:   education.txt
        modified:   profile.txt
        modified:   test.py

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.txt

no changes added to commit (use "git add" and/or "git commit -a")

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory
        modified:   background.txt
        modified:   education.txt
        modified:   profile.txt
        modified:   test.py

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.txt

no changes added to commit (use "git add" and/or "git commit -a")

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git commit -m "save"
[main f437aea] save
 5 files changed, 15 insertions(+)
 create mode 100644 readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git status
On branch main
nothing to commit, working tree clean

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ ls
background.txt  education.txt  profile.txt  readme.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git rm readme.txt
rm 'readme.txt'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ ls
background.txt  education.txt  profile.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git branch b1

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git branch b2

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git branch b3

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git branch b4

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git checkout b1
D       readme.txt
Switched to branch 'b1'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ ls
background.txt  education.txt  profile.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ notedpad profile.txt
bash: notedpad: command not found

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ notepad profile.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ add .
bash: add: command not found

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ git status
On branch b1
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   profile.txt
        deleted:    readme.txt


jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ git commit -m "save"
[b1 caa0b58] save
 2 files changed, 10 insertions(+), 1 deletion(-)
 delete mode 100644 readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ git checkout b2
Switched to branch 'b2'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ ls
background.txt  education.txt  profile.txt  readme.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ notedpad education.txt
bash: notedpad: command not found

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ notepad education.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ git rm readme.txt
rm 'readme.txt'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ git commit -m "save"
[b2 c0cd343] save
 2 files changed, 6 insertions(+), 1 deletion(-)
 delete mode 100644 readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ ls
background.txt  education.txt  profile.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ git checkout b3
Switched to branch 'b3'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ ls
background.txt  education.txt  profile.txt  readme.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ notedpad background.txt
bash: notedpad: command not found

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ notepad background.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ git rm readme.txt
rm 'readme.txt'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ git commit -m "save"
[b3 683b712] save
 2 files changed, 5 insertions(+), 1 deletion(-)
 delete mode 100644 readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ ls
background.txt  education.txt  profile.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ git rm test.py
rm 'test.py'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ git commit -m "save"
[b3 87ddae7] save
 1 file changed, 3 deletions(-)
 delete mode 100644 test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ ls
background.txt  education.txt  profile.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ git checkout main
Switched to branch 'main'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ ls
background.txt  education.txt  profile.txt  readme.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git checkout b4
Switched to branch 'b4'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ ls
background.txt  education.txt  profile.txt  readme.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ notepad read.me

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ notepad readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ notepad readme.txt

