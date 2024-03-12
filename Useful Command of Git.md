# Command of Git



> Configure Git using user_name and email

```bash
$ git config--global user.name "user_name"
$ git config--global user.email "user_email"
```

> Clone a specific branch from the repository

```bash
$ git clone -b <Branch_name> <Repo_URL>
```

> Create a new branch

```bash
$ git branch <branch_name>
```

> Switch Branch

```bash
$ git checkout <branch_name>
```

> Create a local branch and switch to that branch

```bash
$ git checkout -b <branch_name>
```

> Fetch update

```bash
$ git fetch <remote> <branch> # get information from remote
$ git checkout <branch_name> # update local info accordingly
```

> Delete Branches

```bash
# delete original branches
$ git delete -d <branch_name>  
# delete remote branches
$ git push origin --delete <branch_name> 
```

> Track all the changes made, point out untracked files

```bash
$ git status
```

> Commit

```bash
$ git commit
# add commit message
$ git commit -m "Commit message"
# write commite message for already staged files
$ git commit -am "Commit message"
# edit the last commit
$ git commit -amend
```

> Remove a collection of files

```bash
$ git rm <file_name>
```

> Merge to the main branch

```bash
git merge <branch_name>
```

> Re-base

```bash
git rebase <branch_name>
```

> Pull

```bash
# pull a remote repository
$ git pull
# This command is equivalent to $ git fetch origin head
```

> Check changes in the Branch

```bash
$ git pull <RemoteName> <BranchName>
```

> Blame

```bash
$ git blame 
```

> Initialize 

```bash
$ git init
```

> Add

```bash
# add one or more files to the staging area
$ git add
```

> Log

```bash
# provide a list of all commits made on a branch
$ git log
# view changes(briefly)
$ git log --oneline
# view changes(detail)
$ git log --summary
```

> Difference

```bash
# view the changes you have made to the file
$ git diff
# show difference between working directory and last commit 
$ git diff HEAD
```

> Configuration

```bash
# List all variables set in config file, along with values
$ git config --list
```

> Revert

```bash
$ git revert <commit_id>
```





