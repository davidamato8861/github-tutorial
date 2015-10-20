# GitHub Tutorial

_by David Amato_

---
## Git vs. GitHub
###Git:
* Git is *version control*, which means that Git controls and tracks changes of your code.
* Git also runs in the command line, easy for editing code.
* Use the command `git` `something` to tell Git what to do. 

###Github:
* Github also runs in the command line.
* Collaboration is a big part of Github, because people can make changes to someone else's project(s).
* Visit `github.com`, sign up, and start editing code.

###Difference:
* Git is not on the cloud, meaning that you cannot save code with Git.
* You can only save code, on the cloud, with Github.  


---
## Initial Setup
###Setting up your Github account:
* First, you must type your remote host on Github.
* You have to type in your `username`, `email` and `password`to sign up.

###SSH Key:
* This key is found on your coding program/platform.
* You can use it to connect your `localhost` with `Github`.
* Just `Ctrl/Command-C` the SSH Key and `Ctrl/Command-V` it into your remote, 
in order to sync changes you make in your coding platform.

###Git Config:
* When you first initialize Git, it starts allowing you to use the command `git config`.
* This lets you setup your `user.name` and `user.email`, so that when you make changes to code, Git will know who made those changes. 


---
## Repository Setup
###Initializing Git:
* When you first connect your remote to your local,you have to use `git init`.
* Use this in the command line in order to initialize Git.

###Add and Commit:
* When you first create a file, you need to save the changes.
* Then you need to type `git add`, the file name and `git commit -m`.
* By doing this, your saving any changes you have made to a specific file.

###First Github Repository:
* Once you setup your Github account, you are asked to create your first repository.
* This is a folder or directory that holds all things that your create on your coding program, inside of it.
* You are allowed to create an infinite amount of repositories on your Github account!

###Remote:
* Remember your Github? This is what your remote is!
* A remote is basically just the program that allows you to track changes that you have made, or commits, in a specific repository.
* So when you first set this up, you can use `git remote add [shortname] [URL]`.
* This adds a remote to your local, or your coding platform.


---
## Workflow & Commands
###Status:
*  Do this frequently in order to know what files are added to the stage or _ready to take a snapshot_.
*  Use `git status` to view added files.

###Adding files:
* Add changed files to the stage by typing `git add File Name Goes Here`.
* This sets up the file to be saved, or _having the picture taken_.

###Commiting files:
* This takes a picture or snapshot of the file
* Use `git commit -m File Name (from stage) Goes Here`, to _take a picture_.

###Pushing files:
* This just _pushes_ all changes/commits you have made to your remote repository.
* If you go on Github, you will see any commits you have made on your machine.