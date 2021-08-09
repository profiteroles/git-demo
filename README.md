# Git Demo
This is a git demo git repo with a list of commands as a cheat sheet.

## Creating a local Repo

1) Change into the reuired folder
- MAC : cd ~/Source/Repos
  
PC: 
```bash 
  cd ~%HOME%\Source\Repos
```

2) Create New Folder
   
```bash 
  mkdir Project-Name
```

3) Change into folder
   ```bash
   cd Project-Name
   ```
4) initialise with git
   ```bash
   git init
   ```
5) Change Master to Main
```bash
   git branch -m master main
```
6) Check the Status
   ```bash
   git status
   ```
7) create a /gitignore
   MAC:
   ```bash
   touch .gitignore
   ```
   PC:
   ```bash
   echo "" > .gitignore
   ```
8) Add required "ignores to the .gitignore file. Recommend that you use a known .gitignore
or head to [http://gitignore.io](htt[://gitignore.io])
9) Check the status
   ```bash
   git status
   ```
10) Add and Commit the basic changes to version control
    
    ```bash
    git commit .
    ```
11) Verify Commit 
```bash 
git status 
```
Aside: We added a README.md (this file) at this point, and added it to Version control

###Adding file to Tracking

```bash
git add filename
git add folderaname/*
git add -A
git add.
```

### Cheking the Logs
```bash
git log
```
### Create a branch
```bash
git branch -v
```

### Change branch
```bash
git checkout BRANCH-NAME
```

### Merging the Branch
```bash
git checkout main
git status
git merge BRANCH-NAME
git status
git log
```

## Remote Repositories
Before you can use a remote repository (repo) you need to have created it on the remore system.

We'll use Github for this purpose, other remote repositories that use git are also valid.

## Create a Remote Repo

1) Head to github.com
2) if you don't have an account, create a github account
3) Create a new repo making sure that: 
   - Don't add a README.md
   - Don't add a Liscense
   - Don't add .gitignore
   - In other words: Don't add anything to the **blank** repo
4) 


|Heading|Heading|Heading|
|-|-|-|
|Content for cell|Another bit|Last bit|

