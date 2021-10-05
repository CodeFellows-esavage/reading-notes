# Revisions and the Cloud
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
- git commit -m "message": commits code with message
- git status: determine state of file
- git add:
- git push origin master: pushes code to head
- git remote: view the short names of all specified remote handles

### Repositories
You can either import a repository or clone a repository.

Structure:
1. Working Directory - files stored here
2. Index - used for staging
3. Head - most recent commit (you are here spot on a map)
