# GitHub Tutorial

##### _by Joshua Fleary_

---
## Git vs. GitHub

**Git** is version control that keeps snapshots of your code and runs in the command line. You have access to files and you are able to edit files, add files, remove files and commit them. 


**Github** stores code on the internet and visually tracks changes that are made. Github makes it simple to collaborate with others. Github **requires git** to work and also runs in the command line.


The **_difference_** between git and github is that git is to manage your code, fix it, make edits and github hosts the git repositories 

---
## Initial Setup
To create a **[Github]( https://github.com/join?source=header-home)** account go on their website. (link in blue)



---
## Repository Setup
Init (initialize) creates a new repository. This is the first command that you will use when using Git, without git init, most git commands cannot be used because you are not in a repository, you are outside an initialized repo without git init.
```
git init 
```

---
## Workflow & Commands





Status allows you too see where you are in your code. It displays the current directory and what staging area you are in. It is command to see which files have been edited since the last commit.
```
git status 
```
Add . allows you too add all files that has been changed... adds evertything except deleted or renamed files.
```
git add . 
```
Adds all files even the deleted and renamed files.
```
git add -all
```
commit lets you too record your changes/edits to your repository.  
```
git commit
```

push allows you too add your commits you have done on your local repo to a remote.
```
git push
```

---
## Rolling Back Changes
 To undo text
 ```
 Git checkout (filename)
```
To undo add
```
Git reset HEAD filename
```
To undo commit
```
Git reset --soft HEAD~1
```
To undo all 3: Text, add, commit
```
Git reset --hard HEAD~1
```

---
## Error Handling
If you did "init"in the wrong directory then.

---
## Collaboration