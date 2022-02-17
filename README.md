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
git log -stat -To see detailed log<br />
git log -patch -To see much more detailed info with the lines added/deleted you can also search for using sha eg :/19a297c <br />
git show shaFromOneline - eg: git show b25dd4a to show a specific change if it shows device null no deletion has been made<br />

when we use git add filename or git add . we are moving a file from working directory to staging area
<br />
git commit is used for making the commit
git commit -m "what has been changed" helps to add comment directly, without the -m it will open a text editor. <br />
git diff -To see the changes in a file
