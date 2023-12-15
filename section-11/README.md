### Github: The Basics


```sh

# Cloning the repo
git clone https://github.com/gabrielecirulli/2048.git


# Viewing remotes
git remote -v


# Adding a Remote
# origin is just the name of remote
git remote add origin https://github.com/bunyaminmrcn/git-github-bootcamp.git

```

##### Remote options

![Remote](../assets/images/2023-12-15%2011-46-18.png "Remote")



```sh

# pushing the repo of some branch( master ) to some origin ( origin )
git push origin master

# push cats to master branch
git push origin cats:master

# up-stream of repo
# remembers the main branch and origin then you can call like only this `git push`
git push -u origin master

# move the main branch
git branch -M main
```