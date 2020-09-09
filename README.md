# IS601-Fall2020

## Course Live Session Recordings
1. [Session 1](https://youtu.be/P4yXk5-iw_I)
2, [Session 2 - Part 1](https://youtu.be/vXJ1qrnfamM)
3. [Session 2 - Part 2](https://youtu.be/-yGJA4rvcmo)

## Course Resources

1. [Markdown Mastery - Language to write HTML easily](https://guides.github.com/features/mastering-markdown/)



# Git Help

## Definitions 

1.  Branching is the idea of creating a copy of the code and then adding new code for a task on a branch, and allows 
you to merge branches together.  For example, I will create a new branch for my task and then I will create a pull request to have my branch mergeed to the master branch.



## Steps to work with GIT

1. Create a project on WebStorm
2. Add Readme.md and .gitignore to the project files
3. Go to VCS->Import to Version Control->Share on Github
4. Share it and make the first initial commmit
5. Your Partner needs to clone the repository 
6. You need to add your partners's githubID to the project on github.  On Github go to settings and then manage access, 
where you will click add collaborators to add them to the project.  You use their GithubID 
7. Once your partner clones the repository they need to create a branch, complete their task, and then push the branch
 to the repository.  Note: If you get access denied then you have not been added as a collaborator to the repo.
8.  Once you push the code branch up to GitHub then create a pull request to have the code merged and someone needs to 
merge it.
9.  Once the code is merged then you need to pull the code by going to VCS->GIT->Pull in webstorm and remember to check the master branch for the pull 
10. Rinse and repeat steps 7, 8, 9 to do more tasks.

Note: If you put a bunch of code in a branch then you will cause problems.  You need to keep your branches and commits 
organized because there will be merge conflicts, which means GIT can't figure out what code should be merged 
automatically and then you will be prompted to manually edit the files on GitHub or on WebStorm.

## Forking vs Cloning 

Forking copies the repo on Git to your account and allows to push and make changes.  Cloning copies the code to your
 local computer.  To send changes to a cloned repo, you need to be an admin / collaborator, which the owner of the repo needs to add you to.  Forking allows you to take a copy and not be added as a collaborator, but still send your changes to the origin / original repo you forked from, so that the owner of the repo can incorporate your changes without needing to add you as a collaborator.

###  Forking Steps
1.  Click fork on source repo to copy to your account
2.  Once the source repo is copied clone it from your account
3.  Branch, edit, commit, push changes to your account
4.  Create a new pull request and click "Compare across forks" to send a pull request to the source repository, make 
sure you have the correct account and repos selected on the left i.e. the source account.
5.  Once the pull request is created then the owner of the source acc
