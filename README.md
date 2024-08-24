# Git Assignment - <Your jakub-stach>

a. What is an issue?

An issue is a ticket that allows us to track bugs, tasks, and different parts of the project.

b. What is a pull request?

It's a request to merge changes from one branch to another, usually from a side branch to the main one.

c. Describe the steps to open a pull request?

Create a branch, commit changes, push the changes to the remote repository, then git fetch, then git pull origin main and resolve conflicts if any.

d. Describe the steps to add a collaborator to a repository (share write permissions)

(at least on the web) Go to the repository's setting on GitHub, go to collaborators, then indicate who can collaborate and how (username/email), and click 'add'.

e. What is the difference between git and GitHub?

Git is a version control system for code whereas GitHub is a platform for hosting repositories and collaboration.

f. What does git diff do?

Shows the changes (or differences) between a current directory and the index or between commits.

g. What is the main branch?

This is the 'source of truth' primary, stable, production code.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

We should not push our changes directly to the main branch as that may mess up our whole code/work, best to work off of side branches, test them, then merge changes into the main branch once we are satisfied.
