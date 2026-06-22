# Git

## What problem does Git solve?
The problem that git solves is being able to track every change that is made to a project. This makes it possible to go back to previous versions on a project. Additonally, it allows for different people to collaborate on the same codebase without overwriting and interfering with each other's work. 

## What is a repository?
A repository is a folder that git is tracking. It contains a hidden .git subfolder that stores the entire history of a project. A repository contains both the project files and their complete history.

## What is a commit?
A commit is a snapshot of the staged changes of your project at a point in time. This can be though of as a checkpoint, kind of like a video game where you want to save your progress. 

## What is the staging area?
The staging area is where you decide what changes you want to commit. Its the period in between your working files and a commit. 

## Why do branches exist?
Branches exist so that you can work on something new while not affecting the main codebase. By default, the codebase is on a branch called main. Whenever you want to make changes to the codebase, maybe for a feature or bug, a branch allows to have a parallel copy of the code to modify. This allows for multiple people to work on a codebase with minimal conflicts, but also keeps main stable and prevents new features to disturb the (hopefully working) main branch. 

## Commands I learned
git pull, git init, git clone, git add, git add ., git commit -m '', git commit -am '', git add /filename && git commit -m '', git push, git branch /branchname, git checkout /branchname

## Git vs GitHub
Git is the version control software that tracks changes locally on your computer. GitHub is an online platform that hosts Git repositories and provides collaboration tools like pull requests, issues, and code reviews.

## Things I found confusing
What I found confusing was the SSH keys/passwords. I need to follow up on that. 