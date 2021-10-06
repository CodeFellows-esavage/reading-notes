# Revisions and the Cloud
Documents Referenced: [Git Tutorial: A Comprehensive Guide](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

## Version Control
By utlizing a version control system (VCS) one is able to access multiple states of a file or project. This is used to easily track/compare modifications or revert any changes that go south.

There are three (3) types of version control:
1. Local Version Control - a VSC consisting of a database on a computers hard drive
2. Centralized Version Control (CVCS) - database on server that can be accessed by mutliple people (allows for collaboration)
3. Distributed Version Control (DVCS) - allows for collaboration be eliminates single point of failure associated with CVCS server side database by mirroring repositories which can be used as backups.

## Git (a DVCS)
### Git Overview
Git is the most utlized VCS in the world since its adaptation in 2005. It relies mostly on local operations and acts as a gate keeper that will track every single change to minimize opportunities for data loss.

Three States of a File:
1. Committed - data stored securly on a local database.
2. Modified - file is changed but not commited to the database.
3. Staged - updated file is flagged to be commited
 
### Git Commands
- git config --list: shows general configuration settings (user, email, etc)
- git help *command* (see list of commands)
   - -a, -g: list available subcommands and some concept guides.
   - commands: reference list of subcommands (line above) to get additional details regarding a specific command
   - git: for an overview of the system
- git clone "github SSH link": clones the code from github **(ONCE CLONED DO NOT MODIFY CODE DIRECTLY ON GITHUB)**
- git commit -m "brief message with why change was made": commits code with message
- git status: determine state of file
- git add "filename.ext" or .: "filename" will prep one file, "." will prep all files in the repository
- git push origin master: pushes code to head
- git remote: view the short names of all specified remote handles
   - git remote -v: shows URLS next to corresponding short names

### Repositories
You can either import a repository or clone a repository from GitHub.

See git clone command.

Repository Structure:
1. Working Directory - files stored here
2. Index - used for staging
3. Head - most recent commit (you are here spot on a map)

### Saving Changes
- Files are either Tracked or Untracked
  - Tracked files were part of the most recent snapshot and can be modified, unmodified, or staged.
  - Untracked files were not part of the most recent snapshot. When you create a new file or page, that will be untracked until commited to the most recent snapshot.

ACP Steps:
1. git status
2. (A) git **a**dd filename.ext or .
3. git status
4. (C) git **c**ommit -m "brief message of why change was made"
5. git status
6. (P) git **p**ush origin main
