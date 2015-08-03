## Branches
### Find all branches which are not merged into master
```
git branch --no-merged master
```
### Find all commits which are not merged into master
```
git cherry -v master <branch>
```
