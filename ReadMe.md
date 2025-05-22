
# Git Exercises
## Bundle1
### Exercise1
``` bash

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision
$ git init
Initialized empty Git repository in C:/Users/Admin/Documents/Documents/Git-exercises-revision/.git/

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (master) 
$ touch index.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (master) 
$ git branch -m main

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git add .

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git commit -m "Here's git learning journey"
[main (root-commit) 5b297e2] Here's git learning journey
 1 file changed, 11 insertions(+)
 create mode 100644 index.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git remote add origin https://github.com/Munezero26200/Git-exercises-revision.git 

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main   

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git push --set-upstream origin main  
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.       
Delta compression using up to 2 threads   
Compressing objects: 100% (2/2), done.    
Writing objects: 100% (3/3), 390 bytes | 43.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Munezero26200/Git-exercises-revision.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git checkout -b dev
Switched to a new branch 'dev'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git checkout -b test
Switched to a new branch 'test'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (test)   
$ git checkout dev
Switched to branch 'dev'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git branch -d test
Deleted branch test (was 5b297e2).
```
### Exercise2
```bash

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision
$ git init
Initialized empty Git repository in C:/Users/Admin/Documents/Documents/Git-exercises-revision/.git/

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (master) 
$ touch index.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (master) 
$ git branch -m main

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git add .

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git commit -m "Here's git learning journey"
[main (root-commit) 5b297e2] Here's git learning journey
 1 file changed, 11 insertions(+)
 create mode 100644 index.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git remote add origin https://github.com/Munezero26200/Git-exercises-revision.git 

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main   

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git push --set-upstream origin main  
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.       
Delta compression using up to 2 threads   
Compressing objects: 100% (2/2), done.    
Writing objects: 100% (3/3), 390 bytes | 43.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Munezero26200/Git-exercises-revision.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git checkout -b dev
Switched to a new branch 'dev'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git checkout -b test
Switched to a new branch 'test'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (test)   

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ touch home.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git add home.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git stash
Saved working directory and index state WIP on dev: 5b297e2 Here's git learning journey

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ touch about.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git add about.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git stash
Saved working directory and index state WIP on dev: 5b297e2 Here's git learning journey

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ touch team.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git add team.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git stash
Saved working directory and index state WIP on dev: 5b297e2 Here's git learning journey

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git stash pop about.html
error: about.html is not a valid reference
Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git stash list
stash@{0}: WIP on dev: 5b297e2 Here's git 
learning journey
stash@{1}: WIP on dev: 5b297e2 Here's git 
learning journey
stash@{2}: WIP on dev: 5b297e2 Here's git 
learning journey

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git stash show stash@{0}
 team.html | 14 ++++++++++++++
 1 file changed, 14 insertions(+)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git stash show stash@{1}
 about.html | 13 +++++++++++++
 1 file changed, 13 insertions(+)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)
$ git stash show stash@{2}
 home.html | 11 +++++++++++
 1 file changed, 11 insertions(+)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ReadMe.md

Dropped stash@{1} (82b9e2f3603c3b4379b2da181c496717aaf6b52e)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git stash pop stash@{2}
fatal: log for 'stash' only has 2 entries

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ReadMe.md

Dropped stash@{1} (b6c37f7f1ffff11d121880ef79c1c896ad4f3735)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git add .

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git commit -m "Here's the current changes about git and github content"
[dev 1a4d724] Here's the current changes about git and github content
 3 files changed, 93 insertions(+)        
 create mode 100644 ReadMe.md
 create mode 100644 about.html
 create mode 100644 home.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev    

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git push --set-upstream origin dev
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.       
Delta compression using up to 2 threads   
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1.43 KiB | 489.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Munezero26200/Git-exercises-revision/pull/new/dev   
remote:
To https://github.com/Munezero26200/Git-exercises-revision.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.
Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (cfdf6c3312e29d10f31f376a6656d47820888630)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)    
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html


Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (dev)Documents/Git-exercises-revision (dev)    
$ git checkout -b ft/bundle-2 
Switched to a new branch 'ft/bundle-2'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/bundle-2)
$ touch services.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/bundle-2)
$ git add services.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/bundle-2)
$ git commit -m "Here's our services."
[ft/bundle-2 43c1a5d] Here's our services. 1 file changed, 14 insertions(+)
 create mode 100644 services.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/bundle-2)
$ git push
fatal: The current branch ft/bundle-2 has 
no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/bundle-2)
$ git push --set-upstream origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.       
Delta compression using up to 2 threads   
Compressing objects: 100% (3/3), done.    
Writing objects: 100% (3/3), 539 bytes | 179.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Munezero26200/Git-exercises-revision/pull/new/ft/bundle-2

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/bundle-2)Documents/Git-exercises-revision (ft/bundle-2)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:  
        ReadMe.md
Please commit your changes or stash them before you switch branches.
Aborting

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/bundle-2)
$ git add ReadMe.md

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/bundle-2)
$ commit -m "Here's the Exercise1 on bundle2"
bash: commit: command not found

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/bundle-2)
$ git commit -m "Here's the Exercise1 on bundle2"
[ft/bundle-2 7b2969d] Here's the Exercise1 on bundle2
 1 file changed, 462 insertions(+)        

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git pull
remote: Enumerating objects: 1, done.     
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 906 bytes | 64.00 KiB/s, done.
From https://github.com/Munezero26200/Git-exercises-revision
   5b297e2..b107f4b  main       -> origin/main
Updating 5b297e2..b107f4b
Fast-forward
 ReadMe.md     | 69 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++     
 about.html    | 13 +++++++++++
 home.html     | 11 ++++++++++
 services.html | 14 ++++++++++++
 4 files changed, 107 insertions(+)       
 create mode 100644 ReadMe.md
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 services.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/service-redesign)
$ git add services.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/service-redesign)
$ git commit -m "Here's the contact incase
 you want to reach out"
[ft/service-redesign d85acd9] Here's the contact incase you want to reach out       
 1 file changed, 1 insertion(+)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.       
Delta compression using up to 2 threads   
Compressing objects: 100% (3/3), done.    
Writing objects: 100% (3/3), 396 bytes | 132.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:      
remote:      https://github.com/Munezero26200/Git-exercises-revision/pull/new/ft/service-redesign
remote:
To https://github.com/Munezero26200/Git-exercises-revision.git
 * [new branch]      ft/service-redesign -> ft/service-redesign

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/service-redesign)
$ git checkout main 
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git add service.html
fatal: pathspec 'service.html' did not match any files

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$  git add services.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git commit -m "Here is the number you can call for any help you might need"
[main 7886f71] Here is the number you can 
call for any help you might need
 1 file changed, 1 insertion(+)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git push
To https://github.com/Munezero26200/Git-exercises-revision.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Munezero26200/Git-exercises-revision.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git pull
   b107f4b..587acfd  main       -> origin/mainmain
Auto-merging services.html                ices.html
CONFLICT (content): Merge conflict in servthen commit the result.ices.html
Automatic merge failed; fix conflicts and Documents/Git-exercises-revision (main|MERGING)
then commit the result.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main|MERGING)
$ git checkout ft/service-redesign
error: Your local changes to the following files would be overwritten by checkout:  
        services.html
Please commit your changes or stash them before you switch branches.
Aborting

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main|MERGING)
$ git add services.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main|MERGING)
$ git commit -m "Here's the our contacts"
[main addc1af] Here's the our contacts

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)   
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/service-redesign)
$ git fetch

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/service-redesign)
$ git diff main..ft/service-redesign
diff --git a/services.html b/services.htmlindex bbfcfef..5e9d6f1 100644
--- a/services.html
+++ b/services.html
@@ -11,6 +11,5 @@
   <p>We can show you how to track your code, fix mistakes, and work with a team.</p>de, fix mistakes, and work with a team.</p on GitHub.</p>>                                         to munezeroa95@gmail.com</p>
   <p>We also help you share your projects8</p> on GitHub.</p>
   <p>For the other information reach out 

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/service-redesign)
$ git fetch

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/service-redesign)
$ git merge main
Updating d85acd9..addc1af
Fast-forward
 services.html | 1 +
 1 file changed, 1 insertion(+)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/service-redesign)
$ git commit -m "Now main and ft/service-redesign is merged"
On branch ft/service-redesign
nothing to commit, working tree clean     

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/service-redesign)
$ git log --oneline --graph --all
*   addc1af (HEAD -> ft/service-redesign, main) Here's the our contacts
main) Here's the our contacts
|\                                        erge pull request #3 from Munezero26200/ft/service-redesign
| *   587acfd (origin/main, origin/HEAD) Merge pull request #3 from Munezero26200/ft Here's the contact incase you want to reach out/service-redesign
| |\                                      l for any help you might need
| | * d85acd9 (origin/ft/service-redesign) Here's the contact incase you want to reaezero26200/ft/bundle-2ch out
| |/                                      rcise1 on bundle2

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/service-redesign)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.     
Delta compression using up to 2 threads   
Compressing objects: 100% (6/6), done.    
Writing objects: 100% (6/6), 640 bytes | 91.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), completed with 2 local objects.
To https://github.com/Munezero26200/Git-exercises-revision.git
   d85acd9..addc1af  ft/service-redesign -> ft/service-redesign

