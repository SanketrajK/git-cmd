git --version :- This command will display the version of git installed on your system.
git config --global user.name "Your Name" :- This command will set your name in git.
git config --list :- This will show you all the settings that you have changed.
git config --global user.name "Your Email" :- This command will set your Email in git.

#Main Work start from these commands:-

git status :- At any point you can run the this command to see the current state of your repository.
git init :- git init command will create a new folder on your system and initialize it as a git repository.
git add . :- This command will add all the files in the current directory to the staging area.
git commit -m "Your commit message" :- This command will commit all the files in the staging.
git log:- This command will show you the history of your repository.
git log --oneline :- the --oneline flag to show only the commit message.
git branch :- This command lists all the branches in the current repository.
git branch <branch-name> :- This command will create a new branch with the given name.
git checkout -b <branch-name> :- This command will create a new branch and switch to it
git checkout <branch-name> :- This command will switch to the given branch.
git switch <branch-name> :- This command switches to the given branch
git merge <branch-name> :- This command merges the given branch into the main(or where you want to merge) branch.
git branch -m <old-branch-name> <new-branch-name> :- You can rename a branch using the given command
git branch -d <branch-name> :- This command will delete the given branch.