# Basic git commands I use:
1. Initialize.
```
git init
```
2. Set remote origin. 
```
git remote add origin https://github.com/kshithijiyer/MyNotes.git
```
3. Add the files.
```
git add .
```
4. Commit the changes
```
git commit -m "updated"
```
5. Upload to github 
(This step will ask for username and password of your github account.)
```
git push -f origin master
```
6. Download for github
```
git clone https://github.com/kshithijiyer/MyNotes.git
```
7. Adding a fork
```
git remote add fork https://github.com/<username>/repo
```
8. Pushing to fork repo
```
git push fork <BranchName>
```
9. Adding command to squash commits
```
git rebase -i HEAD~x
x: the number of pactches you want to squash
```
10. Reset all code on master
```
git reset --hard gerrit/master
gerrit should be changes to origin if the repo is on github.
```
