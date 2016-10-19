# Git Commands
Description required about the documentation.

### Configuration
Configure user information for all local repositories

Setting names to the commit attaches
```sh
$ git config --global user.name "[name]"
```

Setting email id to the commit attaches
```sh
$ git config --global user.email "[email address]"
```


### Creating a repositories
Creating a new repository or using the existing repo's URL

Creating a new local repository
```sh
$ git init [project-name] 
```

Using an existing repo
```sh
$ git clone [repo-url] 
```

### Workflow
Checking status, adding a file, making commits, pushing the changes, etc.

To check the latest modification done in the project
```sh
$ git status
```

To check the difference between changes that has not yet staged
```sh
$ git diff
```

To add the file which contains the required changes
```sh
$ git add [file-name]
```

To commit the changes
```sh
$ git commit -m "[message]"
```

To push the changes to the desired branch
```sh
$ git push origin -u [branch name]
```
or
```sh
$ git push origin [branch name]
```


### Group Changes
Listing all the branches in the repo
```sh
$ git branch
```

Create a new branch
```sh
$ git branch [branch-name]
```

Checkout to different branches
```sh
$ git checkout [branch name]
```

Combining the specified branch into current branch
```sh
$ git merge [branch name]
```

Delete a branch
```sh
$ git branch -d [branch name]
```

Forcibly delete the branch
```sh
$ git branch -D [branch name]
```

Listing version history for the current branch
```sh
$ git log
```

Resetting the changes from previous or specified commit
```sh
$ git reset [commit]
```

Fetch all remotes
```sh
$ git fetch --all
```

Stash
```sh
git stash
git pull origin develop
git stash pop
```
case study:
  - Saving the current changes without commiting.
  - Taking the upstream changes that are relevant to what you are doing.
  - coming back to what you were doing.
