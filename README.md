Control-Task

Version

ANSWERS



**What is Version Control?**

 Version control is a system that records changes to files or sets of files over time so that you can recall a specific version later. It allows multiple people to collaborate on a project, track who made many changes, and revert to previous states if something goes wrong.



2\. Difference between Git and GitHub:



* **Git** is a distributed version control system that runs on your local machine. It tracks changes in your file and helps you manage different versions of your project.

&nbsp; 

* **GitLab** is a web-based platform that hosts Git repositories online. It adds collaboration features like pull requests, issues, and project management tools, and it allows you to share your code with others.



3\. **Three GitHub Alternatives**



**a.** **GitLab:** A web-based DevOps lifecycle tool that provides a Git repository manager with CI/CD pipelines, issue tracking, and more.



**b. Bitbucket:** A Git repository hosting service owned by Atlassian, integrated with Jira and Trello.



**c. SourceForge:** An older platform that hosts open- source projects, providing version control via Git, Mercurial, and Subversion. 



4\. **Difference between Git fetch and Git Pull**



* **Git fetch:** Git fetch downloads new data from the remote repository (like new branches or commits) but does \*\***not**\*\* integrate them into your working files. It just updates your local copy of remote branches.



* **git pull** Does two things: it fetches the latest changes and then immediately merges them into your current branch (like running 

"Git fetch" followed by "Git merge"). It updates both your remote tracking branches and your working directory.



5\. **Explain Git rebase in simple terms and the command:** Rebasing is a way to move or combine a sequence of commits to a new base commit.



**\*\*Commands\*\***

**``` bash**

**git rebase <branch-name>** 



6\. **Explain in simple terms git cherry-pick and the command for it**



**Cherry-picking** allows you to choose a specific commit from one branch and place it on another branch. It's like picking a single commit and moving it elsewhere, without moving the whole branch. 



**\*\*Command\*\***

**git cherry-pick <commit-hash>**

