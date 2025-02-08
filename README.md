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