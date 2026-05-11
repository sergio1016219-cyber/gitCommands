clone #creates a local copy of an existing remote repostiory on computer, including all files, history, and branches
checkout -b # a combination command that creates a new branch and immediately switches you to it
status # displays the current state of your working directory and staging area
push # Uploads your local branch commits to a remote repository
-u # set the upstream tracking reference
pull # Downloads changes from a remote repository and immediately intergrates them into your current local branch
add # moves changes from your wokring directory to the staging area
commit #saves a snapshot of your staged changes to the local repostiroys history
- m # allows you to include a commit message directly in the command
- a # automatically stages all modiefied and deleved files before commiting
- am # A common shortcut combining -a and -m
branch # Used to list create or delete branches
-a # lists all branches including both local and remote tracking branches
-d # Deletes a specified branch locally once it has been fully merged into another branch
merge # Combines the history and changes from one branch into your current active branch.