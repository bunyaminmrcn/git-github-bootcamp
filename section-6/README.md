### Section 6 - Working With Branches


```sh

# Viewing all branches
git branch

# create a branch, but does not switch 
git branch branch-name

# to  switch
git switch branch-name

# create a branch with checkout option, but switches
git checkout branch-name

# create & switches
git switch -c branch-name

# deletes a branch
git branch -D branch-name

# move the current branch to another
git branch -m 2000s


```


### Some Tips
```sh

# these are same
git add . && git commit -m "commit message"
git commit -a -m "commit message"

```