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
Use your school email or email you normally use

An **SSH Key** is needed for your git and github work. To set it up go to [c9.io](https://c9.io/joshuaf4837)
1. Go to settings
2. Click on the **SSH keys** tab
3. copy and paste the second SSH key that is given
4. Go to the **[github](github.com)** website 
5. select settings and go to the SSH and GPG keys 
6. click on "new SSH key"
7. Lastly, paste the SSH key you have copied on cloud9
---
## Repository Setup
1. To create a repository go onto Github with your signed in account. Once you are there click on the "+" icon and select new repository. After that
give your repository a name
2. select if you want it to be public or private
3. Click on "create repository"
4. copy the two lines of code that are in the " push an existing repository from the command line" tab
5. Once copied, go to your cloud 9 workspace, press "alt t" to open up your workspace
6. Clone the repository
6. cd into the Repository you have created
```
cd (Filename)
```
7. open the README.md
8. commit with message 
```
 git commit -m ("message")
```
9. paste the two lines of code into the terminal.
10. Your repository is now on Github


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
commit lets you record your changes/edits to your repository.  
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
If you did "init"in the wrong directory then. * NOT DONE *

---
## Collaboration
When you clone, you are making a copy from remote to local.  
*You can clone a repository that is not even yours*  
To clone use:
```
git clone (URL)
```
**ALWAYS cd into the directory after it is cloned**


When you fork on Github, That means you have a remote copy of the other persons remote repository. You are able to clone your remote to local and you are able to push to **your own remote.** 

A **remote** is a common repository for all members to exchange the edits/changes the make. You can push or pull from a remote.

Once you fork a repository and would like to add your changes, You **must submit** a pull request. Your pull request can either be accepted or denied. If accepted, the changes you have made will be on the their local repo.  
If you are recieving requests, you can see them on the pull requests tab and accept or deny which changes you desire and will benefit you. To see the edit/changes use git pull
```
git pull
```

Remember too:  
* clone with ssh key  
* Fork before you clone (if you want to make a copy of the remote repository so you can edit.)
