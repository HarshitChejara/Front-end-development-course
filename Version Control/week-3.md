----------------
Working with Git
----------------




* Git and Github *

1) - What is Git and GitHub?
Git - It is a version control system designed to help users keep track of changes to files within their projects. Git was designed to help 
      with the challenge of tracking all these changes and updates. Git is used predominantly via the command line.
GitHub - GitHub is a Cloud-based hosting service that lets you manage Git repositories from a user interface. A Git repository is used to 
         track all changes to files in a specific folder, and keep a history of all those changes. In this projects can be private or public. Users on GitHub have their own profile which other users can follow. Public projects can accept code contributions from anyone across the globe.

2) - Cloning a repository
You copy the repository from GitHub.com to your local machine. Cloning a repository pulls down a full copy of all the repository data that GitHub.com has at that point in time, including all versions of every file and folder for the project.

3) - How Git works
Create a "repository" (project) with a git hosting tool.
Copy (or clone) the repository to your local machine.
Add a file to your local repo and "commit" (save) the changes.
"Push" your changes to your main branch.
Make a change to your file with a git hosting tool and commit.

4) - Add and Commit
The purpose of the git add command is that I'm essentially prompting git and letting it know that I want to track this file, and that it will be included as part of my commit.

5) - Branches
It allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository. you always create a branch from an existing branch. You can think of them as a way to request a brand new working directory, staging area, and project history.

6) - Remote vs. local
Remote - It refers to any other remote repository to which developers can push changes. This can be a centralized repository, such as one provided by Git hub. The remote code is accessed through a URI which is unique and only accessible to those who have permission.
local - It refers to your machine which can be a laptop, desktop or even a mobile device and is only accessible to you.

7) - Push and pull
Push - using git push uploading the changes to the remote repository.
pull - using git pull retrieve changes from the remote servers and apply them to your local repository.

8) - HEAD
It is one of the files inside the dot git folder. This file refers to the current committee you are viewing. It does not point to any branch, but instead points to a specific commit or the remote repository.

9) - Diff commands
Git diff will compare the previous version of the file with your current one to find any differences. It will then tell you specifically what content has been removed as well as what content has been added to the file. Diff is used to make comparisons against files on your local repository. It can also be used against commits and against branches.

10) - Blame
The git blame command is used to look at changes of a specific file and show the dates, times, and users who made the changes. you can change the format of how the list is displayed. you can see detail changes or the actual commit changes of a specific hash dash ID. 

11) - Forking
A fork is a new repository that shares code and visibility settings with the original “upstream” repository. Forks are often used to iterate on ideas or changes before they are proposed back to the upstream repository, such as in open source projects or when a user does not have write access to the upstream repository.