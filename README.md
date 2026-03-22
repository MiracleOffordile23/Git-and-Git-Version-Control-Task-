# GIT AND VERSION CONTROL

## EXPLANATION OF VERSION CONTROL

Version control also known as source control or revision control is an important software development practice for tracking and managing changes made on code and other files. It is closely related to source code management.

Version control tracks every code change, providing complete history and a single source of truth so teams can experiment safely, roll back if needed and collaborate effectively.
This allows software developers to see the entire history of who changed what at any given time and roll back from the current version to an earlier version if they need to. It also create a single source of truth.

Version control serves as a safety net to protect the source code from irreparable harm, giving the development team the freedom to experiment without fear of causing damage or creating code conflict.

## DIFFERENCE BETWEEN GIT AND GITHUB

### Git and github are closely related tools used for sotfware development. But they serve different roles in managing and colaborating in source code

Git is a distributed version control system used to track and manage code changes locally.
It is designed for speed,data integrity and reliable version tracking.
It supports distributed,non-linear work-flows.
It also enables efficient collaboration for teams and individual.

WHILE

Github is a web-based platform that hosts git repositories and provides collaboration features.
It adds collaboration features such as pull request and issue tracking.
It provides code hosting,review,and team collaboration.

## OTHER GIT ALTERNATIVES

- Codeberg
- Radicle
- AWS CodeCommit

## DIFFERENCE BETWEEN GIT FETCH AND GIT PULL

### Git fetch and git pull are both Git commands used to retrieve update infromation from a remote repository

Git fetch command retrieves the latest commit history from the remote repository, but it does not affect the local working directory.
Git fetch downloads updates from the remote repository.
Git fetch allows you to see what others have commited before merging.
It updates only the remote tracking branches.

WHILE

Git pull is used to fetch all changes from the remote repository to the current working repository.
Git pull fetches and merges updates from the remote repository in one step.
It keeps your branch in sync with the remote branch.
Git pull automatically attempts to merge changes,which can sometimes lead to conflicts.

## GIT REBASE AND COMMAND FOR IT

Git rebase integrates changes by replaying your commits on top of your latest state of another branch creating a cleaner, linear history.
It moves commits to the tip of the target branch.
Git rebase rewrite commit history instaed of creating a merge commit .
It keeps the project linear and easy to read.

### COMMAND FOR REBASE

- git checkout branchname
- git rebase main

## GIT CHERRY-PICK AND COMMAND FOR IT 

Git cherry-pick allows you to apply a specific commit  from one branch onto another without merging the entire branch 
It selectively applies individual commits.
It is useful for hotfixes or targeted changes.
It does not bring full branch history.

### GIT CHERRY-PICK COMMAND 

- git cherry-pick <commit-hash>