## Git Tutorial

https://youtu.be/l2yrJtwoC_E

```ps
git log --all --decorate --oneline --graph
```

git add <file.txt>  or 
git add .

git commit -m "Commit message"


#### To create new file in PowerShell
```ps
New-Item file.md
```

To stage all modified files and commit them at the same time.
```ps
git commit -a -m "Commit message"
```

```ps
git push
```
```ps
git pull
```

```
git fetch
```
```
git clone
```

To go back to a previous commit
```ps
git reset --hard <commitId>
```
View local commit log
```ps
git reflog
```

```ps
git revert <commitID>
```
```ps
git cherry-pick <commitID>
```

Change from Master to Main
```
git branch -M main
```

To link local repo to remote repo.
```ps
git remote add github http://...
```
then
```
git push
```

## Branching
To create a new branch and switch to it 
```
git switch -c NewBranchName
```
