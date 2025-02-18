# git pull : 
Git will not automatically remove or overwrite your uncommitted changes during a git pull. Instead, Git will attempt to apply the remote changes on top of your current state.
However, if the changes from the remote repository conflict with your uncommitted changes, Git will raise an error and prevent the merge from completing. This ensures your work is not lost.
