## Research Questions

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Git is a version control management system that allows you to clone repositories and work on them. create branches and in general manage  your workflow on the computer and share and collaborate with other developers on projects.
Git manages source code.  
2. What is the difference between Git and GitHub?
Github is a hosting service for Git. Git is the actual system that does all the filing and saving and branching and what not.
3. Why do we create a branch?
We create a branch to isolate our work from others work.
4. What is the purpose of a Pull Request?
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
The Git switch command.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
The 'git merge' command allows you to take the changes you've made to several different branches and integrate them into a single branch. The 'git fetch' command allows you to download commits, files and refs from another remote repository into your local repository. Basically the fetch command is what you do when you want to see what everybody else has been working on. The 'git pull' command or request is used to fetch and download content from a remote repository and immediately update the local repository to match that content. This differs from the fetch command in that you are downloading a repository to contribute work on it A.K.A. make some commits and update your own code onto branches that you're working on or have created.
7. What is a merge conflict?
A merge conflict is an event that takes place when Git is unable to automatically resolve differences in code between two commits. Git can merge the changes automatically only if the commits are on different lines or branches. If git can't automatically merge the changes then there is a merge conflict.
8. How do you resolve a merge conflict?
There are two ways to resolve a merge conflict that i've learned about. They are:
1. commit any changes that have been made to a branch and then try merging again.
2. open the file and make the required changes then add and commit the changes you just made.

You can also use a few commands to resolve merge conflicts. These commands are:
- git log --merge: this produces the list of commits that are causing the conflict.
- git diff: this helps you find the differences between the states of repositories or files.
- git checkout: This undoes any changes made to a file or a change of branches.
- git reset --mixed: used to undo the changes to the working directory and the staging area.
- git merge --abort: helps in exiting the merge process and return back to the state before the merging began.
- git reset: used at the time of merge conflict to reset the conflicted files to their original state.
