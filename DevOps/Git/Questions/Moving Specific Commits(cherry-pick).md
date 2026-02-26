
This is the best method if you need to pick specific commits (one or several) and apply them to another branch.

- **Single commit:**
    1. Switch to the target branch: `git checkout target-branch`.
    2. Apply the desired commit by its hash: `git cherry-pick <hash>`.
- **A range of commits:**
    1. Use the range syntax: `git cherry-pick A^..B` (this includes all commits from A to B).
- **Multiple random commits:**
    1. List them separated by spaces: `git cherry-pick <hash1> <hash2> <hash3>`.