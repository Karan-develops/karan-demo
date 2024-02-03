# karan-demo
This is my first git Repository
<br>
Author -> Karan aggarwal :)
// Commands (ls, ls -a)
cd karan-demo -> change directory to karan-demo
git status , git clone <link> , git add . , git add <file name> , git commit -m ""
git push origin main -> make changes (from local to remote repo)
//init (used to create new repo -> from device to git)
to get outside of the directory -> cd ..
create new repo directory -> mkdir <name>
to make a repo into a git repo -> git init

//creating new repo from local to remote
git remote add origin <link>
to verify remote -> git remote -v
to check branch -> git branch
to rename branch -> git branch -M main
git push origin main
set upstream (if we don't wanna write origin main again n again) -> git push -u origin main

//branches
to check branch -> git branch
to rename branch -> git branch -M main
to navigate(jump) between branches -> git checkout <branchname>
to make new branchs -> git checkout -b <new-branchname>
to delete a branch -> git branch -d <branchname>

//merging (way1)
to compare 2 branches,commits,files,etc -> git diff <branchname>
to merge 2 branches -> git merge <branchname>
(way2) -> create a PR (pull request)

//pull command
to pull changes from remote(git) to local -> git pull origin main

//Undoing changes
to undo add changes -> git reset <filename>
to undo commit changes (for 1 commit) -> git reset HEAD~1
**
//git log (to see commit changes history)
to undo multiple commit changes -> git reset <commithash> (obtain from git log)
git reset --hard <commithash> (vs code se bhi changes ht jaenge)

//fork -> a rough copy of others code in our repo