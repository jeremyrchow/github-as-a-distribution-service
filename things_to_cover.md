# Things to Cover
# Definitions
1. Fork vs Branch
- Fork is permanent split
- branch has capabilities to merge back into 

# Pulling from class repository, pushing to your own repository
## Things to do once
1. Fork class repo > personal online repo
2. Clone personal online repo onto a directory on your computer
3. git remote add upstream [class repo URL]
-check using git remote -v

## Things to do DAILY
1. git pull upstream master
2. Push changes regularly
- git add [files, or \*]
- git commit -m "Message to put in commit"
- git push
- don't nee

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
- soft is just your staged files
- mixed is the index that you're currently working on
- hard is index you're working on , files in your computer
--hard is the only flag that will actually delete files
