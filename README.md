# Git-Notes

Source code management (SCM)

### Git Global Config List

git config --list

### Git States

1. Working Directory
2. Staging Area
3. Commit

git init - To initialize a git repository <br />
git Status - To see if any files have been updated <br />
git clone - To clone a remote repository<br />
git log - To see the commits done by the user<br />
git log --oneline - To see short logs<br />
git log --stat -To see detailed log<br />
git log --patch -To see much more detailed info with the lines added/deleted you can also search for using sha eg :/19a297c <br />
git show shaFromOneline - eg: git show b25dd4a to show a specific change if it shows device null no deletion has been made<br />

when we use git add filename or git add . we are moving a file from working directory to staging area
<br />
git commit is used for making the commit
git commit -m "what has been changed" helps to add comment directly, without the -m it will open a text editor. <br />
git diff -To see the changes in a file <br />
git restore --staged filename - To pull a file from staging area back to working directory

.gitignore file is used to ignore files/folder

\* is used as a wildcard match and # is used for comments


### git tag
There are two types of tags
1. Annotated tag [-a](detailed)
2. Light weight tag (No detail)

git tag used for versioning the commits <br>
git tag -a 19a297c -To tag a particular commit <br>
just using git tag will tag the most recent commit <br>
The -a in git tag means annotated tag <br>
git tag -d V1.0 to delete a particular tag <br>

### git branch
git branch is used while adding new functionality fixing bugs without effecting the main branch <br>
git branch - It shows all branches <br>
git branch branchName - To create  a branch <br>
git switch branchName - To switch to a branch <br>
git switch -c branchName - To create and switch to that branch <br>
git tag -d V1.0 to delete a particular tag <br>
