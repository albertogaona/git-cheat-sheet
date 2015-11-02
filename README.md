# git-cheat-sheet
Common-use git commands

Clone existing repository
```
$ git clone ssh://user@domain.com/repository.git
```

Create a new local repository
```
$ git init
```

See current branch and changed/new files in your working directory
```
$ git status
```

Changes to tracked files
```
$ git diff
```

Add all current changes to the next commit
```
$ git add -A
```

Commit changes 
```
$ git commit -m "Comment"
```

Show all commits (newest first)
```
$ git log
```

Show changes on specific file
```
$ git log -p <file>
```
	
Who changed what and when in specific file
```
$ git blame <file>
```

View existing branches
```
$ git branch -a
```
*(Current branch has a leading asterisk)*
	
Switch to branch
```
$ git checkout branch-name
```

Create new branch and switch to it
```
$ git checkout -b new-branch-name
```

Push current branch to remote server 
```
$ git push 
```

Get changes from remote server
```
$ git pull
```


