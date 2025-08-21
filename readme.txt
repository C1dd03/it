
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

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ git status
On branch b4
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory
)
        modified:   readme.txt

no changes added to commit (use "git add" and/or "git commit -a")

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ git add .

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ git commit -m "save"
[b4 e59902d] save
 1 file changed, 343 insertions(+)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ git rm test.py
rm 'test.py'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ git commit -m "save"
[b4 16304aa] save
 1 file changed, 3 deletions(-)
 delete mode 100644 test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ ls
background.txt  education.txt  profile.txt  readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ git checkout main
Switched to branch 'main'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ ls
background.txt  education.txt  profile.txt  readme.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git remote it120_sample ^[[200~https://github.com/C1dd03/it.git~
error: unknown subcommand: `it120_sample'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-
tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename [--[no-]progress] <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <bran
ch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <
remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --[no-]verbose    be verbose; must be placed before a subcomma
nd


jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git remote add it120_sample https://github.com/C1dd03/it.git

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git pull ite120_sample main --allows-unrelated-histories
error: unknown option `allows-unrelated-histories'
usage: git pull [<options>] [<repository> [<refspec>...]]

    -v, --[no-]verbose    be more verbose
    -q, --[no-]quiet      be more quiet
    --[no-]progress       force progress reporting
    --[no-]recurse-submodules[=<on-demand>]
                          control for recursive fetching of submodules

Options related to merging
    -r, --[no-]rebase[=(false|true|merges|interactive)]
                          incorporate changes by rebasing rather than
merging
    -n                    do not show a diffstat at the end of the mer
ge
    --[no-]stat           show a diffstat at the end of the merge
    --[no-]log[=<n>]      add (at most <n>) entries from shortlog to m
erge commit message
    --[no-]signoff[=...]  add a Signed-off-by trailer
    --[no-]squash         create a single commit instead of doing a me
rge
    --[no-]commit         perform a commit if the merge succeeds (defa
ult)
    --[no-]edit           edit message before committing
    --[no-]cleanup <mode> how to strip spaces and #comments from messa
ge
    --[no-]ff             allow fast-forward
    --ff-only             abort if fast-forward is not possible
    --[no-]verify         control use of pre-merge-commit and commit-m
sg hooks
    --[no-]verify-signatures
                          verify that the named commit has a valid GPG
 signature
    --[no-]autostash      automatically stash/stash pop before and aft
er
    -s, --[no-]strategy <strategy>
                          merge strategy to use
    -X, --[no-]strategy-option <option=value>
                          option for selected merge strategy
    -S, --[no-]gpg-sign[=<key-id>]
                          GPG sign commit
    --[no-]allow-unrelated-histories
                          allow merging unrelated histories

Options related to fetching
    --[no-]all            fetch from all remotes
    -a, --[no-]append     append to .git/FETCH_HEAD instead of overwri
ting
    --[no-]upload-pack <path>
                          path to upload pack on remote end
    -f, --[no-]force      force overwrite of local branch
    -t, --[no-]tags       fetch all tags and associated objects
    -p, --[no-]prune      prune remote-tracking branches no longer on
remote
    -j, --[no-]jobs[=<n>] number of submodules pulled in parallel
    --[no-]dry-run        dry run
    -k, --[no-]keep       keep downloaded pack
    --[no-]depth <depth>  deepen history of shallow clone
    --[no-]shallow-since <time>
                          deepen history of shallow repository based o
n time
    --[no-]shallow-exclude <ref>
                          deepen history of shallow clone, excluding r
ef
    --[no-]deepen <n>     deepen history of shallow clone
    --unshallow           convert to a complete repository
    --[no-]update-shallow accept refs that update .git/shallow
    --refmap <refmap>     specify fetch refmap
    -o, --[no-]server-option <server-specific>
                          option to transmit
    -4, --[no-]ipv4       use IPv4 addresses only
    -6, --[no-]ipv6       use IPv6 addresses only
    --[no-]negotiation-tip <revision>
                          report that we have only objects reachable f
rom this object
    --[no-]show-forced-updates
                          check for forced-updates on all updated bran
ches
    --[no-]set-upstream   set upstream for git pull/fetch


jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git pull ite120_sample main --allow-unrelated-histories
fatal: 'ite120_sample' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ remote -v
bash: remote: command not found

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git remote -v
it120_sample    https://github.com/C1dd03/it.git (fetch)
it120_sample    https://github.com/C1dd03/it.git (push)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git push ^C

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git pull it120_sample main --allow-unrelated-histories
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 843 bytes | 70.00 KiB/s, done.
From https://github.com/C1dd03/it
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> it120_sample/main
Merge made by the 'ort' strategy.
 README.md | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git push it120_sample main
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (11/11), 1.07 KiB | 548.00 KiB/s, done.
Total 11 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), done.
To https://github.com/C1dd03/it.git
   2e4028b..49c34b6  main -> main

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git checkout b4
Switched to branch 'b4'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ git push it120_sample b4
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1.64 KiB | 1.64 MiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'b4' on GitHub by visiting:
remote:      https://github.com/C1dd03/it/pull/new/b4
remote:
To https://github.com/C1dd03/it.git
 * [new branch]      b4 -> b4

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ git checkout main
Switched to branch 'main'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git checkout b4 --readme.txt
error: unknown option `readme.txt'
usage: git checkout [<options>] <branch>
   or: git checkout [<options>] [<branch>] -- <file>...

    -b <branch>           create and checkout a new branch
    -B <branch>           create/reset and checkout a branch
    -l                    create reflog for new branch
    --[no-]guess          second guess 'git checkout <no-such-branch>'
 (default)
    --[no-]overlay        use overlay mode (default)
    -q, --[no-]quiet      suppress progress reporting
    --[no-]recurse-submodules[=<checkout>]
                          control recursive updating of submodules
    --[no-]progress       force progress reporting
    -m, --[no-]merge      perform a 3-way merge with the new branch
    --[no-]conflict <style>
                          conflict style (merge, diff3, or zdiff3)
    -d, --[no-]detach     detach HEAD at named commit
    -t, --[no-]track[=(direct|inherit)]
                          set branch tracking configuration
    -f, --[no-]force      force checkout (throw away local modificatio
ns)
    --[no-]orphan <new-branch>
                          new unborn branch
    --[no-]overwrite-ignore
                          update ignored files (default)
    --[no-]ignore-other-worktrees
                          do not check if another worktree is using th
is branch
    -2, --ours            checkout our version for unmerged files
    -3, --theirs          checkout their version for unmerged files
    -p, --[no-]patch      select hunks interactively
    --[no-]ignore-skip-worktree-bits
                          do not limit pathspecs to sparse entries onl
y
    --[no-]pathspec-from-file <file>
                          read pathspec from file
    --[no-]pathspec-file-nul
                          with --pathspec-from-file, pathspec elements
 are separated with NUL character


jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git checkout b4 -- readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git add readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   readme.txt


jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git commit -m "save"
[main 898e037] save
 1 file changed, 343 insertions(+)

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git push ite_sample main
fatal: 'ite_sample' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git push it120_sample main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.48 KiB | 1.48 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/C1dd03/it.git
   49c34b6..898e037  main -> main

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (main)
$ git checkout b1
Switched to branch 'b1'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ ls
background.txt  education.txt  profile.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ git checkout b4 -- readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ git add readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ git commit -m "save"
[b1 b9cc721] save
 1 file changed, 343 insertions(+)
 create mode 100644 readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ git status
On branch b1
nothing to commit, working tree clean

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ git push it120_sample b1
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.97 KiB | 1.97 MiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'b1' on GitHub by visiting:
remote:      https://github.com/C1dd03/it/pull/new/b1
remote:
To https://github.com/C1dd03/it.git
 * [new branch]      b1 -> b1

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b1)
$ git checkout b2
Switched to branch 'b2'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ ls
background.txt  education.txt  profile.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ git checkout b4 -- readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ git add readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ ls
background.txt  education.txt  profile.txt  readme.txt  test.py

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ git commit -m "Save"
[b2 3151883] Save
 1 file changed, 343 insertions(+)
 create mode 100644 readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ git status
On branch b2
nothing to commit, working tree clean

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ git push it120_sample b2
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.80 KiB | 1.80 MiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'b2' on GitHub by visiting:
remote:      https://github.com/C1dd03/it/pull/new/b2
remote:
To https://github.com/C1dd03/it.git
 * [new branch]      b2 -> b2

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b2)
$ git checkout b3
Switched to branch 'b3'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ ls
background.txt  education.txt  profile.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ git checkout b4 -- readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ git add readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ ls
background.txt  education.txt  profile.txt  readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ git commit -m "save"
[b3 9956500] save
 1 file changed, 343 insertions(+)
 create mode 100644 readme.txt

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ git push it120_sample b3
Enumerating objects: 11, done.
Counting objects: 100% (11/11), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 1.98 KiB | 1.98 MiB/s, done.
Total 8 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote:
remote: Create a pull request for 'b3' on GitHub by visiting:
remote:      https://github.com/C1dd03/it/pull/new/b3
remote:
To https://github.com/C1dd03/it.git
 * [new branch]      b3 -> b3

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b3)
$ git checkout b4
Switched to branch 'b4'

jstin@DESKTOP-0J7J0RJ MINGW64 ~/it120_sample (b4)
$ notepad readme.txt

