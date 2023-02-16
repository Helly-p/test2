## Git Practical Exam

###### 1. Pull and Merge difference

- Pull Request

Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub.
Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.

- Merge 
git merge is used to combine two branches. 

```
git merge branch_name
```

###### 2. Rebase
Rebasing is the process of moving or combining a sequence of commits to a new base commit.

```
git rebase branch_name
```

###### 3. Change commit message

1. Using commit --amend
The git commit --amend command is a convenient way to modify the most recent commit and to edit commmit message.

```
git commit --amend
```

2. Using Interactive Rebase
Git interactive rebase allows you to change individual commits, squash commits together, drop commits or change the order of the commits. 
reword(r) is used to edit commit messages.

```
git rebase -i HEAD~5
```

###### 4. Cherry-pick
Cherry-picking in Git stands for applying some commit from one branch into another branch. 

```
git cherry-pick commit_hash
```

###### 5. Drop commit
It resets the current branch tip, and also deletes any changes in the working directory and staging area.

```
git reset --hard
```
