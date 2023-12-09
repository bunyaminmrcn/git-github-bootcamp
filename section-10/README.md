### Undoing Changes & Time Traveling


##### About Head

![Head](../assets/images/2023-12-09%2022-02-18.png "Head")

##### Detach Head

![Detach head](../assets/images/2023-12-09%2022-16-05.png "Detach head")


##### About Head 2

![About head](../assets/images/2023-12-09%2022-24-28.png "About head")


###  Commands

```sh

# go to previous commit so and so fourth
git checkout HEAD~1


# revert changes of dog.txt
git checkout HEAD dog.txt
#or
git checkout -- cat.txt


# restore dog.txt from 2 commits before
git restore --source HEAD~2 dog.txt

git restore  lyrics.txt

```

##### Simple Use Case

```sh

# add to all files with current directory
git add .

# !You might be forget to add to .gitignore to secrets.txt for example
git restore --staged secrets.txt

```

###  Commands
```sh

# hard reset

# Assumed 4 commit you done before
# And you want to delete 2 commits before

git reset --hard commithash # 51494a6

```
##### Reset
![Revert](../assets/images/2023-12-09%2023-45-40.png "Reset")

##### Revert
![Revert](../assets/images/2023-12-09%2023-03-34.png "Revert")