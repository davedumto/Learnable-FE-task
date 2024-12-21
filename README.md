# Learnable-FE-task
This is a repository created in fulfillment my assessment at Learnable 2024 Cohort

# Explain version control.
Version control is a system that tracks changes to files, allowing you to manage and revert to previous versions if needed. It enables collaboration by letting multiple people work on the same project without overwriting each other's changes.

# Explain difference between git and github
Git is a version control system used to track changes in your code or files locally on your computer. GitHub is a cloud-based platform that hosts Git repositories, enabling teams to collaborate, share, and manage code projects online.

# List 3 other github alternatives
1) GitLab
2) BitBucket
3) SourceForge
   
# Explain the difference between git fetch and git pull,
git fetch: Downloads changes from the remote repository but does not merge them into your local branch. This lets you review the updates before integrating them.
git pull: Combines git fetch and git merge, downloading changes and immediately merging them into your current branch.
In short, git fetch is for viewing updates, while git pull is for retrieving and applying them directly.

# Explain in simple terms git rebase and the command for it
Git rebase is a way to move or "reapply" your commits on top of another branch to make your history cleaner and linear. It’s like "replaying" your work onto a new base branch instead of merging it.
* Example command: git rebase <branch-name>

# Explain in simple terms git cherry-pick and the command for it 
Git cherry-pick is a command that allows you to apply a specific commit from one branch into another, without merging the entire branch. It’s like saying, “I just want this one change from over there.
* Example command: git cherry-pick <commit-hash>
