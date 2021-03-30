Fatima Alshira'h
 Version control is a system allows you to revesit various versions of a file or set of files
 I can now know the deffernce between local VCS and CVCs, and I read about DVCS and how much is 
important when we lose backups.
Git  is a DVCS that stores data in a file system made up of snapshots.the git depend on local
operation, and it's track any change happened and save the backups from lose.
Files in Git reside in three main states: committed, modified and staged.
we install Git on a Mac (for Mavericks 10.9 and above).to install the Git you need follow many steps.
(so much steps I can't summarized)...we can creat copy of Git by using clone.

component of Git: 1)Working Directory 2) Index 3) head
We can saving changes by track and untrack . * git status to determaine the status of file.
I learn about tracking and staging in single file and all file.
$ git commit -m “made change x,y,z” to commit one or multiple file change.
$ git commit -m “made change x,y,z” to commit all changes 
after commit change we push changes to a remote repository.
 git stash to commit changes but do not want to lose them 
git stash apply to retrieve the hidden changes.