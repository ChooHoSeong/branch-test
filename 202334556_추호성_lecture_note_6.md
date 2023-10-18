# Lecture Note - Git
---

### Version Control
- changes : Storing data as changes to the base version

- snapshot : Storing data as snapshots

---
- Local : file store in local storage

- Centralized : file store in central storage. road from the central storage

- Distributed : file store in all storage. share and uproad the update.

---
### Git commands
```
//show git version
$git --version
```
##### git config
1. system level : affect all repository
file:/etc/gitconfig
2. global level : affect repository of current user
file:~/.config/git/config
3. local level : specific current repository
file:.git/gitconfig
- Each level overrides values in the previous level : system->global->loca
```
//show config
$git config --list
//show config location
$git config --list --show-origin
//initialize username
$git config --global user.name "[username]"
//intialize email
$git config --global user.email user-email-[email]
//initialize branch name
$git config --global init.defaultBranch [branchname]
```
##### use git
```
//make .git file
$git init
//show git's status
$git status
//add file to staging area for being tracked by git
$git add [filename]
$git add . //add all file
//remove file in staging area
$git rm --cached [filename]

//.gitignore file is file_list including file must untracked
//!!make .gitignore file!!
//modify .gitignore
$nano .gitignore
//commit files to branch
$git commit -m "[commit name]"
//show commits log
$git log
//show recent branch name
$git branch
//rename branch
$git branch -m [original name] [new name]
```
