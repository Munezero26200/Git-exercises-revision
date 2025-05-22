
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
