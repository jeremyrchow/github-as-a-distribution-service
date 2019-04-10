# Overview / Scope
For downloading from a 3rd party repository you don't have push permissions for, then pushing your changes to your own personal repository.

# Things to Cover
# Definitions
1. Fork vs Branch
- Fork is permanent split
- branch has capabilities to merge back into branches on repository
2. What is git clone
- fetch and a merge
3. what's a fetch and a merge?
-fetch takes all the changes up to date on the online master
-merge takes those changes and 
# Pulling from class repository, pushing to your own repository
## Things to do once
1. Fork class repo > personal online repo
2. Clone personal online repo onto a directory on your computer
3. git remote add upstream [class repo URL]
-check using git remote -v

## Things to do DAILY - Metis "Workflow"
1. git pull upstream master
2. Push changes regularly
- git add [files, or \*]
- git commit -m "Message to put in commit"
- git push

## Personal Project Workflow
1. Make Changes
2. Git commands
-git add [files]
-git commit -m "Message for commit"
-git push 

# Conflict merging

## merge conflicts
- when do they happen ( won't happen at metis)

## How do you resolve them
- look for <==== HEAD tag  
- Make changes you want, then delete tag

# Other

## Resetting branch
### Why do a reset
- you've accidentally deleted a file
- you want to start from scratch from a certain point

### Terms to know
-What is an staged index vs working copy
### How to reset:
-git reset [--hard vs --mixed vs --soft]
1. soft is just your staged files
-accidentally staged a file you don't want to push
- you're ok with your last checkpoint, don't want to change it as it is saved

2. mixed is the index that you're currently working on, not your file tree
- you made too many disorganized commits but you want to clean up your commit checkpoints 
- not super often

3. hard is index you're working on , files in your computer
-hard is the only flag that will actually delete files
-you've catastrophically screwed up your computer's file tree and deleted everything
-Loses all changes you've made to trackedf files
-Note: Untracked files don't get reset (new files on your working directory won't get deleted)

## Aliasing (Works on all OS's but i'll demonstrate MAC only)
-filename may change (bashrc vs bash_profile)



# Resources
- https://stackoverflow.com/questions/14894768/in-git-how-is-fetch-different-than-pull-and-how-is-merge-different-than-rebase