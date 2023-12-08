### Section 7 Merging Branches


##### Merge

![Merge Logic](../assets/images/2023-12-07%2021-44-26.png "Merge")

```sh

# merge logic
git switch master
git merge bugfix

```


##### Conflict #1
![Conflict Logic](../assets/images/2023-12-08%2004-27-16.png "Conflict")


##### Conflict #2
![Conflict Logic](../assets/images/2023-12-08%2004-31-49.png "Conflict Instructions")

##### After Resolve conflicts

```sh

# commit changes
git commit -a -m "Resolve conflicts or merge"

```
