---
title: Version Control with Git
date: '2024-03-10'
summary: A short summary on what version control is and how it works
---


## What is Version Control

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

If you are a graphic or web designer and want to keep every version of an image or layout (which you would most certainly want to), a Version Control System (VCS) is a very wise thing to use. It allows you to revert selected files back to a previous state, revert the entire project back to a previous state, compare changes over time, see who last modified something that might be causing a problem, who introduced an issue and when, and more. Using a VCS also generally means that if you screw things up or lose files, you can easily recover. In addition, you get all this for very little overhead.

## How does it work?

Git works by keeping track of changes to files in a project over time. Git stores all the data and metadata for version control in repositories hosted on platforms like GitHub or GitLab. A repository is like a folder that contains all the files and folders for a project which allows collaboration among multiple developeers by providing a central location to 'push' and 'pull' changes on a project. On your personal computer you can keep a local copy of this repository where you can edit your project files (what is known as a local repository). 

Before committing your changes, you stage them in a staging area. This allows you to select which changes you want to include in your commit. When you're raedy to save your changes, you create a commit which is a snapshot of the changes you made. Each commit will have a unique identifier and contain metadata like the author, a timestamp and a message describing the changes. 

Git allows you to create branches, which are kind of like pointers to specific commits. Brancges allow you to work on different features of your project without affecting the main codebase. When you're done with a branch, you can merge it back into the main branch. Git will combine all th changes from all the different branches. Pushing sends your local commits to a remote rpository, while pulling retrieves chnages from the remote repository.



