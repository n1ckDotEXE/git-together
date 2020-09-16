# The Git Cheat Sheet - By Nicholas & Ilya

## What is Git?
Git is a distributed version-control system for tracking changes in source code during software development. It was initially released by Linus Torvalds on April 7, 2005. Git itself does not provide access-control mechanisms because it was designed for operating with other tools that have that ability

## Git `Clone`
The `clone` command is used when you want a local copy of of the repository. The cloned copy is still part of the original repository and any changes that are committed are submitted to the original repository as a collaborator.

## Git `Status`
The `status` command is used for displaying the current state of the working directory. The working directory is the state of the changes (if any) of the repository that have been changed or not. Non-tracked changes are also shown with the `status` command. Any information regarding the committed project history are not shown.

## Git `Log`
Using the `log` command will show the committed snapshots and allows you to list and filter the project history. If you want to search for particular changes, the `log` command will allow you to do that.

Note: The `log` command is for the committed history while the `status` command  is used for controlling the working directory and the staging area.

## Git `Add`
When you want to make changes in the working directory (but not in the staging area), you want to use the `add` command. You can simply use the `-A` flag to stage all changes or name the files independently to only stage select files.

## Git `Commit`
The `commit` command is the function to save changes to the local repository and takes a snapshot of the current state of the project. The version gets bumped up to the next version with many details such as time and changes.

## Git `Push`
Using the `push` command is used to send the current version of the local repository to the remote repository so it could be compared and merged. Once the local repository has been pushed, it must have it's changes approved. It cannot be merged without approval from someone with the ability to do so.
