## Version Control
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes. Through version control, one can revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

## what is Git?
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project 
— called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores
a reference to the already-stored identical version of it.

## seeing your remote

 By running the git remote command, you can view the short names,
 such as “origin,” of all specified remote handles.

### By using git remote -v, you can view all the remote URLs next to their corresponding short names.

#### example 
##### $ cd example
##### $ git remote -v
##### remote1 https://github.com/remote1/example (fetch)
##### remote1 https://github.com/remote1/example (push)

## Branching
Almost every type of Version Control System incorporates branching. By creating branches of a central repository, collaborators
are able to work on a project simultaneously via multiple branches, without affecting this main repository.
