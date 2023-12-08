### The Ins and Outs of Stashing


##### Basic Stash

![Stash](../assets/images/2023-12-08%2020-54-12.png "Stash")

```sh

# basic stash
git stash

# remove from stash stack and apply latest stash
git stash pop

# doesnt pop from latest just apply
git stash apply

# lists stash stack
git stash list


```

##### Stash List

![Stash List](../assets/images/2023-12-08%2021-08-26.png "Stash List")

```sh
# apply some stash
git stash apply stash@{2}

# drop some stash
git stash drop stash@{2}

# clear stash stack
git stash clear

```