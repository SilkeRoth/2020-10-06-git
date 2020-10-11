
# Git Basic notes

## Local

- `git init`: create git repository in current folder
	- you only do this once per repository
	- do not nest git repositories
- `git status`: tells you what is going on in your repository
- `git add <files>`: puts  <files> into the staging area (index)
- `git commit`: commit message for files in staging area
- `git log`: show your log history
	- `git log --oneline`: one line version of your history

- `git diff`: will show you the differnces
	- `git diff --staged: will show you differences in the staging area
	-`git diff HEAD~2`: diff 2 places back from HEAD
	-`git diff <HASH>`:diff 2 locations

- `git checkout <HASH> <FILE>`: revert file
- `git checkout <HASH>`: go to location
- `git checkout master`: go back to master

## Remotes

- `git remote add origin <URL>`: adds the url with the name "origin"

- `git push origin master`: sends master branch on local computer

- github allows you to do changes online using the pensil (plain text files)
