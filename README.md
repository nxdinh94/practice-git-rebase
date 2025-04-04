# Push commits to another branch

## Step-01: create and switch to the new branch B

    git checkout -b B

## Step-02: Add changes in the new local branch

    git add . //or specific file(s)

## Step-03: Commit the changes

    git commit -m "commit_message"

## Step-04: Push changes to the new branch B. The below command will create a new branch B as well remotely

    git push origin B

i created a branch named [xuan_dinh_branches] at [basic_calculator] commit
and then i push a commit named "add scss".
when main branch have a new commit, i intergrate it into my [xuan_dinh_branches]
and the graph will show

# How to Resolve Merge Conflicts in Git?

- There are a few steps that could reduce the steps needed to resolve merge conflicts in Git.
- Step 1: The easiest way to resolve a conflicted file is to open it and make any necessary changes.
- Step 2: After editing the file, we can use the git add a command to stage the new merged content.
- Step 3: The final step is to create a new commit with the help of the git commit command.
- Step 4: Git will create a new merge commit to finalize the merge.

# Rebase Best Practices
- While git rebase undoubtedly keeps your commit history cleaner, there are a few things to be mindful of:
- Use rebase only for local branches. Do not rebase branches others are working on. Rebase changes the commithistory, and others will not know about it.
- Regularly fetch and rebase your local branches to stay up-to-date with the main branch. Conflicts become messy! Rebase early and often.


# Fast-forward merge happen when merge another branch while current branch have no commit
# prevent fast-forward merge : git merge <some_branch> --no-ff

# main changed 3

# feature branch changed