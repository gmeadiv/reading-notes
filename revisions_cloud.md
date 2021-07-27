# revisions_and_the_cloud
Notes for Lesson 3

## Version Control
- Local Version Control
  - one database on my hard drive that stores changes to files
- Centralized Version Control
  - single server storing all changes and file versions and can be accessed by various clients
- Distributed Version Control
  - weakpoint of CVS is the server is a single point of failure
  - DVCS allows clients to create mirrored repositories 
  - Git is a DVCS
  - 
## Git 
- snapshots
  - saved version of project = "commit"
- local operations
- tracking changes
- loss of data
- states
  1. committed: data is stored securely in a local database
  2. modified: file has been changed but not committed
  3. staged: flagged a file's changed version to be committed in the next snapshot

## Workflow
- local repository structure
  1. working dirctory: the actual files reside here (add)
  2. index: the area used for staging (commit)
  3. head: points to the most recent commit
- saving changes
  - tracked files can be modified, unmodified, or staged
  - untracked files were not in the last snapshot and don't reside in the staging area
  - (after cloning a repository, files have tracked status and are unodified because the've been checked out but not edited
- the life cycle of file status
  1. after editing, Git flags it as modified
  2. stage the modified file
  3. commit staged changes
- check file status (git status)
- tracking and staging a new file
  - single file: git add filename
  - all files: $ git add *
- committing a file
  - git commit -m "insert message here"
  - committing all changes: git commit -a
- pushing changes
  - git push origin main
- stashing changes
  - git stash: not ready to commit changes but don't want to lose them
  - git stash apply: when ready to continue working on changes

## Remote Repositories
- Cloned repositories 
- Seeing your remotes
  - git remote: view short names (ie origin) of all specified remote handles
  - git remote -v: view all the remote URLs next to corresponding short names
