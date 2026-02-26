Use these if you want to integrate all changes from one branch into another.

- **Rebase:** Moves your commits and places them on top of the target branch's latest commits, creating a linear history.

``` Bash
git checkout feature-branch
git rebase target-branch
```

**Merge:** Creates a special "merge commit" that joins the histories of both branches, preserving the branching structure.

``` Bash
git checkout target-branch
git merge feature-branch

```
