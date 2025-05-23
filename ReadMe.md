
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
   ```
   ### Exercise2
   ```bash
   Documents/Git-exercises-revision (ft/team-
page)
$ git checkout main
error: Your local changes to the following
 files would be overwritten by checkout:  
        ReadMe.md
Please commit your changes or stash them b
efore you switch branches.
Aborting

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/
Documents/Git-exercises-revision (ft/team-
page)
$ git add ReadMe.md

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/
Documents/Git-exercises-revision (ft/team-
page)
$ git commit -m" Here is terminal history 
of exercise2 bundle2"
[ft/team-page d4e5b75]  Here is terminal h
istory of exercise2 bundle2
 1 file changed, 5 insertions(+), 1 deleti
on(-)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/
Documents/Git-exercises-revision (ft/team-
page)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2
 commits.
  (use "git push" to publish your local co
mmits)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/
Documents/Git-exercises-revision (main)   
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/
Documents/Git-exercises-revision (ft/conta
ct-page)
$ git checkout ft/team-page 
Switched to branch 'ft/team-page'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/
Documents/Git-exercises-revision (ft/team-
page)
$ git log
commit d4e5b75a52371c3a624d450734d336c17da7511b (HEAD -> ft/team-page)
Author: Munezero26200 <alinemunezero920@gmail.com>
Date:   Thu May 22 12:06:52 2025 +0200

commit d4e5b75a52371c3a624d450734d336c17da
7511b (HEAD -> ft/team-page)
Author: Munezero26200 <alinemunezero920@gm
ail.com>
Date:   Thu May 22 12:06:52 2025 +0200    

     Here is terminal history of exercise2
 bundle2

commit 5469f50f8f19cb7fc1a65b0656aebaad8e0
9a427 (origin/ft/team-page)
Author: Munezero26200 <alinemunezero920@gm
Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page)
$ git cherry-pick d4e5b75a52371c3a624d450734d336c17da7511b
Auto-merging ReadMe.md
CONFLICT (content): Merge conflict in ReadMe.md
error: could not apply d4e5b75...  Here is terminal history of exercise2 bundle2
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".
hint: Disable this message with "git config set advice.mergeConflict false"

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page|CHERRY-PICKING)
$ git status
On branch ft/contact-page
You are currently cherry-picking commit d4e5b75.
  (fix conflicts and run "git cherry-pick --continue")
  (use "git cherry-pick --skip" to skip this patch)
  (use "git cherry-pick --abort" to cancel the cherry-pick operation)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   ReadMe.md

no changes added to commit (use "git add" and/or "git commit -a")

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page|CHERRY-PICKING)
$
 *  History restored 


Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page|CHERRY-PICKING)cises-revision (ft/contact-page|CHERRY-PICKING)
$ git add .

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page|CHERRY-PICKING)
$ git commit -m"Here's the change"
[ft/contact-page 65bf74c] Here's the change
 Date: Thu May 22 12:06:52 2025 +0200      
 1 file changed, 428 insertions(+)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page)
$ git push origin ft/contact-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 3.31 KiB | 1.65 MiB/s, done.   
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Munezero26200/Git-exercises-revision/pull/new/ft/contact-page
remote:
To https://github.com/Munezero26200/Git-exercises-revision.git
 * [new branch]      ft/contact-page -> ft/contact-page     

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ touch faq.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ git add faq.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ git commit -m "This page contains the ideas, please feel f
ree"
[ft/faq-page b8534e6] This page contains the ideas, please feel free
 1 file changed, 11 insertions(+)
 create mode 100644 faq.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 3.82 KiB | 279.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Munezero26200/Git-exercises-revision/pull/new/ft/faq-page
remote:
To https://github.com/Munezero26200/Git-exercises-revision.git
 * [new branch]      ft/faq-page -> ft/faq-page

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ get checkout ft/team-page
bash: get: command not found

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ get checkout ft/team-page
bash: get: command not found

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ get checkout ft/team-page
bash: get: command not found

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ cv
bash: cv: command not found

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ git checkout  ft/team-page
Switched to branch 'ft/team-page'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$ git log
commit d4e5b75a52371c3a624d450734d336c17da7511b (HEAD -> ft/team-page)
Author: Munezero26200 <alinemunezero920@gmail.com>
Date:   Thu May 22 12:06:52 2025 +0200
Revert " Here is terminal history of exercise2 bundle2"

     Here is terminal history of exercise2 bundle2
Date:   Thu May 22 12:03:27 2025 +0200
                                                            eam-page)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$ git revert d4e5b75a52371c3a624d450734d336c17da7511b       
[ft/team-page 53aadff] Revert " Here is terminal history of cises-revision (ft/team-page)
exercise2 bundle2"
 1 file changed, 1 insertion(+), 5 deletions(-)             exercise2 bundle2"

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)                               cises-revision (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 578 bytes | 115.00 KiB/s, done.Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Munezero26200/Git-exercises-revision.git
   5469f50..53aadff  ft/team-page -> ft/team-page

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$ git add ReadMe.md

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$ git commit -m "Here is the terminal history of exercise1 bundle3"
[ft/team-page 649b1a6] Here is the terminal history of exercise1 bundle3
 1 file changed, 274 insertions(+)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$   git push --set-upstream origin ft/team-page
Enumerating objects: 5, done.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)cises-revision (ft/team-page)
$ git checkout ft/faq-page
Switched to branch 'ft/faq-page'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git fetch
remote: Enumerating objects: 19, done.
remote: Counting objects: 100% (17/17), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 9 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (9/9), 4.58 KiB | 29.00 KiB/s, done.From https://github.com/Munezero26200/Git-exercises-revision   587acfd..bbb914c  main            -> origin/main
   65bf74c..dcd9a9e  ft/contact-page -> origin/ft/contact-page
   b8534e6..39e8c2e  ft/faq-page     -> origin/ft/faq-page

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git status
On branch main
Your branch is behind 'origin/main' by 7 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)

nothing to commit, working tree clean

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git pull
Updating addc1af..bbb914c
Fast-forward
 ReadMe.md | 424 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 team.html |  13 ++
 2 files changed, 437 insertions(+)
 create mode 100644 team.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git commit -m"the new changes"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git branch list

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git branch
  dev
  ft/bundle-2
  ft/contact-page
  ft/faq-page
  ft/home-page-redesign
  ft/service-redesign
  ft/team-page
  list
* main

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git add .

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git commit -m "Here's the changes on ReadMe file"
[main b1691e7] Here's the changes on ReadMe file
 1 file changed, 3 insertions(+), 1 deletion(-)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 348 bytes | 348.00 KiB/s, done.Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Munezero26200/Git-exercises-revision.git
   bbb914c..b1691e7  main -> main

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign)
$ git rebase main
Auto-merging ReadMe.md
CONFLICT (content): Merge conflict in ReadMe.md
error: could not apply 65bf74c... Here's the change
hint: Resolve all conflicts manually, mark them as resolved 
with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
--continue".                                                ip".
hint: You can instead skip this commit: run "git rebase --sk, run "git rebase --abort".ip".                                                        Conflict false"
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
hint: Disable this message with "git config set advice.mergecises-revision (ft/home-page-redesign|REBASE 1/2)Conflict false"
Could not apply 65bf74c... Here's the change

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git add home.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git commit -m"about my progress sofar"
[detached HEAD 4c5421c] about my progress sofar
 1 file changed, 1 insertion(+)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push
fatal: You are not currently on a branch.
To push the history leading to the current (detached HEAD)  
state now, use

    git push origin HEAD:<name-of-remote-branch>


Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$  git push origin HEAD:<name-of-remote-branch>
bash: syntax error near unexpected token `newline'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push origin HEAD:ft/home-page-redesign
error: The destination you provided is not a full refname (i.e.,
starting with "refs/"). We tried to guess what you meant by:
- Looking for a ref that matches 'ft/home-page-redesign' on 
the remote side.
- Checking if the <src> being pushed ('HEAD')
  is a ref in "refs/{heads,tags}/". If so we add a corresponding
  refs/{heads,tags}/ prefix on the remote side.

Neither worked, so we gave up. You must fully qualify the ref.
hint: The <src> part of the refspec is a commit object.
hint: Did you mean to create a new branch by pushing to     
hint: 'HEAD:refs/heads/ft/home-page-redesign'?
error: failed to push some refs to 'https://github.com/Munezero26200/Git-exercises-revision.git'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push origin ft/home-page-redesign
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Munezero26200/Git-exercises-revision/pull/new/ft/home-page-redesign
remote:
To https://github.com/Munezero26200/Git-exercises-revision.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
 ```
 ## Bundle4
 ### Exercises2
 ```bash
 Documents/Git-exercises-revision (ft/team-
page)
$ git checkout main
error: Your local changes to the following
 files would be overwritten by checkout:  
        ReadMe.md
Please commit your changes or stash them b
efore you switch branches.
Aborting

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/
Documents/Git-exercises-revision (ft/team-
page)
$ git add ReadMe.md

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/
Documents/Git-exercises-revision (ft/team-
page)
$ git commit -m" Here is terminal history 
of exercise2 bundle2"
[ft/team-page d4e5b75]  Here is terminal h
istory of exercise2 bundle2
 1 file changed, 5 insertions(+), 1 deleti
on(-)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/
Documents/Git-exercises-revision (ft/team-
page)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2
 commits.
  (use "git push" to publish your local co
mmits)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/
Documents/Git-exercises-revision (main)   
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/
Documents/Git-exercises-revision (ft/conta
ct-page)
$ git checkout ft/team-page 
Switched to branch 'ft/team-page'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/
Documents/Git-exercises-revision (ft/team-
page)
$ git log
commit d4e5b75a52371c3a624d450734d336c17da7511b (HEAD -> ft/team-page)
Author: Munezero26200 <alinemunezero920@gmail.com>
Date:   Thu May 22 12:06:52 2025 +0200

commit d4e5b75a52371c3a624d450734d336c17da
7511b (HEAD -> ft/team-page)
Author: Munezero26200 <alinemunezero920@gm
ail.com>
Date:   Thu May 22 12:06:52 2025 +0200    

     Here is terminal history of exercise2
 bundle2

commit 5469f50f8f19cb7fc1a65b0656aebaad8e0
9a427 (origin/ft/team-page)
Author: Munezero26200 <alinemunezero920@gm
Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page)
$ git cherry-pick d4e5b75a52371c3a624d450734d336c17da7511b
Auto-merging ReadMe.md
CONFLICT (content): Merge conflict in ReadMe.md
error: could not apply d4e5b75...  Here is terminal history of exercise2 bundle2
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".
hint: Disable this message with "git config set advice.mergeConflict false"

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page|CHERRY-PICKING)
$ git status
On branch ft/contact-page
You are currently cherry-picking commit d4e5b75.
  (fix conflicts and run "git cherry-pick --continue")
  (use "git cherry-pick --skip" to skip this patch)
  (use "git cherry-pick --abort" to cancel the cherry-pick operation)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   ReadMe.md

no changes added to commit (use "git add" and/or "git commit -a")

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page|CHERRY-PICKING)
$
 *  History restored 


Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page|CHERRY-PICKING)cises-revision (ft/contact-page|CHERRY-PICKING)
$ git add .

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page|CHERRY-PICKING)
$ git commit -m"Here's the change"
[ft/contact-page 65bf74c] Here's the change
 Date: Thu May 22 12:06:52 2025 +0200      
 1 file changed, 428 insertions(+)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page)
$ git push origin ft/contact-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 3.31 KiB | 1.65 MiB/s, done.   
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Munezero26200/Git-exercises-revision/pull/new/ft/contact-page
remote:
To https://github.com/Munezero26200/Git-exercises-revision.git
 * [new branch]      ft/contact-page -> ft/contact-page     

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ touch faq.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ git add faq.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ git commit -m "This page contains the ideas, please feel f
ree"
[ft/faq-page b8534e6] This page contains the ideas, please feel free
 1 file changed, 11 insertions(+)
 create mode 100644 faq.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 2 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 3.82 KiB | 279.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Munezero26200/Git-exercises-revision/pull/new/ft/faq-page
remote:
To https://github.com/Munezero26200/Git-exercises-revision.git
 * [new branch]      ft/faq-page -> ft/faq-page

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ get checkout ft/team-page
bash: get: command not found

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ get checkout ft/team-page
bash: get: command not found

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ get checkout ft/team-page
bash: get: command not found

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ cv
bash: cv: command not found

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ git checkout  ft/team-page
Switched to branch 'ft/team-page'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$ git log
commit d4e5b75a52371c3a624d450734d336c17da7511b (HEAD -> ft/team-page)
Author: Munezero26200 <alinemunezero920@gmail.com>
Date:   Thu May 22 12:06:52 2025 +0200
Revert " Here is terminal history of exercise2 bundle2"

     Here is terminal history of exercise2 bundle2
Date:   Thu May 22 12:03:27 2025 +0200
                                                            eam-page)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$ git revert d4e5b75a52371c3a624d450734d336c17da7511b       
[ft/team-page 53aadff] Revert " Here is terminal history of cises-revision (ft/team-page)
exercise2 bundle2"
 1 file changed, 1 insertion(+), 5 deletions(-)             exercise2 bundle2"

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)                               cises-revision (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 2 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 578 bytes | 115.00 KiB/s, done.Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Munezero26200/Git-exercises-revision.git
   5469f50..53aadff  ft/team-page -> ft/team-page

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$ git add ReadMe.md

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$ git commit -m "Here is the terminal history of exercise1 bundle3"
[ft/team-page 649b1a6] Here is the terminal history of exercise1 bundle3
 1 file changed, 274 insertions(+)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)
$   git push --set-upstream origin ft/team-page
Enumerating objects: 5, done.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/team-page)cises-revision (ft/team-page)
$ git checkout ft/faq-page
Switched to branch 'ft/faq-page'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/faq-page)
$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git fetch
remote: Enumerating objects: 19, done.
remote: Counting objects: 100% (17/17), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 9 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (9/9), 4.58 KiB | 29.00 KiB/s, done.From https://github.com/Munezero26200/Git-exercises-revision   587acfd..bbb914c  main            -> origin/main
   65bf74c..dcd9a9e  ft/contact-page -> origin/ft/contact-page
   b8534e6..39e8c2e  ft/faq-page     -> origin/ft/faq-page

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git status
On branch main
Your branch is behind 'origin/main' by 7 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)

nothing to commit, working tree clean

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git pull
Updating addc1af..bbb914c
Fast-forward
 ReadMe.md | 424 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 team.html |  13 ++
 2 files changed, 437 insertions(+)
 create mode 100644 team.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git commit -m"the new changes"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git branch list

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git branch
  dev
  ft/bundle-2
  ft/contact-page
  ft/faq-page
  ft/home-page-redesign
  ft/service-redesign
  ft/team-page
  list
* main

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git add .

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git commit -m "Here's the changes on ReadMe file"
[main b1691e7] Here's the changes on ReadMe file
 1 file changed, 3 insertions(+), 1 deletion(-)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 348 bytes | 348.00 KiB/s, done.Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Munezero26200/Git-exercises-revision.git
   bbb914c..b1691e7  main -> main

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign)
$ git rebase main
Auto-merging ReadMe.md
CONFLICT (content): Merge conflict in ReadMe.md
error: could not apply 65bf74c... Here's the change
hint: Resolve all conflicts manually, mark them as resolved 
with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
--continue".                                                ip".
hint: You can instead skip this commit: run "git rebase --sk, run "git rebase --abort".ip".                                                        Conflict false"
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
hint: Disable this message with "git config set advice.mergecises-revision (ft/home-page-redesign|REBASE 1/2)Conflict false"
Could not apply 65bf74c... Here's the change

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git add home.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git commit -m"about my progress sofar"
[detached HEAD 4c5421c] about my progress sofar
 1 file changed, 1 insertion(+)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push
fatal: You are not currently on a branch.
To push the history leading to the current (detached HEAD)  
state now, use

    git push origin HEAD:<name-of-remote-branch>


Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$  git push origin HEAD:<name-of-remote-branch>
bash: syntax error near unexpected token `newline'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push origin HEAD:ft/home-page-redesign
error: The destination you provided is not a full refname (i.e.,
starting with "refs/"). We tried to guess what you meant by:
- Looking for a ref that matches 'ft/home-page-redesign' on 
the remote side.
- Checking if the <src> being pushed ('HEAD')
  is a ref in "refs/{heads,tags}/". If so we add a corresponding
  refs/{heads,tags}/ prefix on the remote side.

Neither worked, so we gave up. You must fully qualify the ref.
hint: The <src> part of the refspec is a commit object.
hint: Did you mean to create a new branch by pushing to     
hint: 'HEAD:refs/heads/ft/home-page-redesign'?
error: failed to push some refs to 'https://github.com/Munezero26200/Git-exercises-revision.git'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push origin ft/home-page-redesign
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Munezero26200/Git-exercises-revision/pull/new/ft/home-page-redesign
remote:
To https://github.com/Munezero26200/Git-exercises-revision.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git add ReadMe.md

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git checkout main
M       ReadMe.md
Warning: you are leaving 1 commit behind, not connected to
any of your branches:

  4c5421c about my progress sofar

If you want to keep it by creating a new branch, this may be a good time
to do so with:

 git branch <new-branch-name> 4c5421c

Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git commit -m"Here is terminal history of exercise2 bundle3"
[main 573d5df] Here is terminal history of exercise2 bundle3
 1 file changed, 442 insertions(+), 1 deletion(-)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push
To https://github.com/Munezero26200/Git-exercises-revision.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Munezero26200/Git-exercises-revision.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git pull
remote: Enumerating objects: 8, done.
remote: Counting objects: 100% (8/8), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (4/4), 1.89 KiB | 36.00 KiB/s, done.
From https://github.com/Munezero26200/Git-exercises-revision
   b1691e7..b05df37  main                  -> origin/main
   b8534e6..545abb0  ft/home-page-redesign -> origin/ft/home-page-redesign
Auto-merging ReadMe.md
CONFLICT (content): Merge conflict in ReadMe.md
Automatic merge failed; fix conflicts and then commit the result.
error: failed to push some refs to 'https://github.com/Munezero26200/Git-exercises-revision.git'                        cises-revision (ft/home-page-redesign|REBASE 1/2)
hint: Updates were rejected because the tip of your current 
branch is behind                                            it
hint: its remote counterpart. If you want to integrate the remote changes,                                              ero26200/Git-exercises-revision.git'
hint: use 'git pull' before pushing again.                  branch is behind
hint: See the 'Note about fast-forwards' in 'git push --helpemote changes,' for details.
                                                            ' for details.
Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)           cises-revision (ft/home-page-redesign|REBASE 1/2)
$ it pull origin main
bash: it: command not found

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git pull origin main
error: You have not concluded your merge (MERGE_HEAD exists).
hint: Please, commit your changes before merging.
fatal: Exiting because of unfinished merge.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git commit -m "new change on readme file"
[main 5bb1fc4] new change on readme file

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
Compressing objects: 100% (5/5), done.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)cises-revision (ft/home-page-redesign|REBASE 1/2)           econdPart-gitExercises-revision.git
$ git remote add git-copy https://github.com/Munezero26200/SecondPart-gitExercises-revision.git                         cises-revision (ft/home-page-redesign|REBASE 1/2)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git add home.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git commit -m"Here's more clarification about our content"[main f6ec731] Here's more clarification about our content
 1 file changed, 1 insertion(+), 1 deletion(-)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git branch --show-current
main

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 358 bytes | 179.00 KiB/s, done.Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Munezero26200/Git-exercises-revision.git
   5bb1fc4..f6ec731  main -> main

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push git-copy main
Enumerating objects: 55, done.
Counting objects: 100% (55/55), done.
Delta compression using up to 2 threads
Compressing objects: 100% (54/54), done.
Writing objects: 100% (55/55), 16.46 KiB | 543.00 KiB/s, done.
Total 55 (delta 26), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (26/26), done.
To https://github.com/Munezero26200/SecondPart-gitExercises-revision.git
 * [new branch]      main -> main

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)cises-revision (ft/home-page-redesign|REBASE 1/2)
$ git checkout -b ft/footer
Switched to a new branch 'ft/footer'
                                                            cises-revision (ft/home-page-redesign|REBASE 1/2)
Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git branch --show-current
ft/footer                                                   cises-revision (ft/home-page-redesign|REBASE 1/2)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git add services.html

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git commit -m" There is no need phone number, is ommitted 
now"
[ft/footer 2ea78f9]  There is no need phone number, is ommitted now
 1 file changed, 1 deletion(-)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push origin ft/footer
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 330 bytes | 330.00 KiB/s, done.Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/Munezero26200/Git-exercises-revision/pull/new/ft/footer
remote:
To https://github.com/Munezero26200/Git-exercises-revision.git
 * [new branch]      ft/footer -> ft/footer

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git checkout ft/squashing
Switched to branch 'ft/squashing'

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git merge --squash ft/footer
Updating f6ec731..2ea78f9
Fast-forward
Squash commit -- not updating HEAD
 services.html | 1 -
 1 file changed, 1 deletion(-)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git add .

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git commit -m"footer changes squashing"
[ft/squashing aafe114] footer changes squashing
 1 file changed, 1 deletion(-)

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push origin ft/squashing
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 316 bytes | 316.00 KiB/s, done.Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/Munezero26200/Git-exercises-revision/pull/new/ft/squashing
remote:
To https://github.com/Munezero26200/Git-exercises-revision.git
 * [new branch]      ft/squashing -> ft/squashing
```
## Bundle5
### Exercise2
```bash

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)ts/Documents/Git-exercises-revision (ftme-/home-page-redesign|REBASE 1/2)        
$ git clone https://github.com/Munezero26200/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done 
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects:   9% (1/11remote: Compressing objects:  18% (2/11remote: Compressing objects:  27% (3/11remote: Compressing objects:  36% (4/11remote: Compressing objects:  45% (5/11remote: Compressing objects:  54% (6/11remote: Compressing objects:  63% (7/11remote: Compressing objects:  72% (8/11remote: Compressing objects:  81% (9/11remote: Compressing objects:  90% (10/1remote: Compressing objects: 100% (11/1remote: Compressing objects: 100% (11/11), done.
Receiving objects:  58% (63/107), 1.28 
Receiving objects:  59% (64/107), 1.28 
Receiving objects:  60% (65/107), 1.28 
Receiving objects:  61% (66/107), 1.28 
Receiving objects:  62% (67/107), 1.28 
Receiving objects:  63% (68/107), 1.28 
Receiving objects:  64% (69/107), 1.28 
Receiving objects:  65% (70/107), 1.28 
Receiving objects:  66% (71/107), 1.28 
Receiving objects:  67% (72/107), 1.28 
Receiving objects:  68% (73/107), 1.28 
Receiving objects:  69% (74/107), 1.28 
Receiving objects:  70% (75/107), 1.28 
Receiving objects:  71% (76/107), 1.28 
Receiving objects:  72% (78/107), 1.28 
Receiving objects:  73% (79/107), 1.28 
Receiving objects:  74% (80/107), 1.28 
Receiving objects:  75% (81/107), 1.28 
Receiving objects:  76% (82/107), 1.28 
Receiving objects:  77% (83/107), 1.28 
Receiving objects:  78% (84/107), 1.28 
Receiving objects:  79% (85/107), 1.28 
Receiving objects:  80% (86/107), 1.28 
Receiving objects:  81% (87/107), 1.28 
Receiving objects:  82% (88/107), 1.28 
Receiving objects:  83% (89/107), 1.28 
Receiving objects:  84% (90/107), 1.28 
Receiving objects:  85% (91/107), 1.28 
Receiving objects:  86% (93/107), 1.28 
Receiving objects:  87% (94/107), 1.28 
Receiving objects:  88% (95/107), 1.28 
Receiving objects:  89% (96/107), 1.28 
Receiving objects:  90% (97/107), 1.28 
Receiving objects:  91% (98/107), 1.28 
Receiving objects:  92% (99/107), 1.28 
Receiving objects:  93% (100/107), 1.28Receiving objects:  94% (101/107), 1.28Receiving objects:  95% (102/107), 1.28Receiving objects:  96% (103/107), 1.28remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 92 (from 1)
Receiving objects:  97% (104/107), 1.28Receiving objects:  98% (105/107), 1.28Receiving objects:  99% (106/107), 1.28Receiving objects: 1eiving objects:  98% (105/107), 1.28Receiv (107/107), 1.95 MiB | 2.90 MiB/s, done.ing objects:  99% (106/107), 1.28Receiving objects: 100% (107/107), 1.28Receiving objects: 100% (107/107), 1.95 MiB | 2.90 MiBDocuments/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)/s, done.
Resolving deltas: 100% (5/5), done.       

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git add .
warning: adding embedded git repository: git-cafe-exercise
hint: You've added another git repository 
inside your current repository.
hint: Clones of the outer repository will 
not contain the contents of
hint: the embedded repository and will not know how to obtain it.
hint: If you meant to add a submodule, use:
hint:
hint:   git submodule add <url> git-cafe-exercise
hint:
hint: If you added this path by mistake, you can remove it from the
hint: index with:
hint:
hint:   git rm --cached git-cafe-exercise 
hint:
hint: See "git help submodule" for more information.
hint: Disable this message with "git config set advice.addEmbeddedRepo false"       

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git commit -m"Here's the change on index.html file"
[ft/squashing a370935] Here's the change on index.html file
 2 files changed, 644 insertions(+), 1 deletion(-)
 create mode 160000 git-cafe-exercise

Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push
fatal: The current branch ft/squashing has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/squashing

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Admin@DESKTOP-JJ9VPBQ MINGW64 ~/Documents/Documents/Git-exercises-revision (ft/home-page-redesign|REBASE 1/2)
$ git push --set-upstream origin ft/squashing
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.       
Delta compression using up to 2 threads   
Compressing objects: 100% (3/3), done.    
Writing objects: 100% (3/3), 1.75 KiB | 224.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Munezero26200/Git-exercises-revision.git
   aafe114..a370935  ft/squashing -> ft/squashing
branch 'ft/squashing' set up to track 'origin/ft/squashing'.
```