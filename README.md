# Git-Cheat-Sheet-
No need to remember all the commands nows and brainstorm each time to before using them, use this cheat sheet to ease yourself and just keep practising the stuff for better understanding.


# Git Cheat Sheet

Git is a distributed version control system that helps developers collaborate on projects of any scale.



## Setup your Git username:
With the command below you can configure your user name:

```bash
  git config --global user.name “sarthak”
```



## Setup your Git user email:
This command lets you setup the user email address you'll use in your commits.

```bash
git config --global user.email “sarthakk.arora1@gmail.com"
```
## Initialize a Empty Git repo:
Everything starts from here. The first step is to initialize a new Git repo locally in your project root. You can do so with the command below:

```bash
git init
```
## Add a file to the staging area in Git:

The command below will add a file to the current directory. Just replace "filename_here"  with the name of the file you want to add to the directory.
```bash
git add filename_here
```
Or if you want to add all the files present in the directory not just a single file, then the command is:
```bash
git add .
```
