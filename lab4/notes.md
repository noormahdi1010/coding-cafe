\# Lab 4 Notes



\## Question 1

`--global` applies the Git name and email setting to every repository on this computer. Without it, the setting would apply only to the current repository.



\## Question 2

`ls -Force` showed the hidden `.git` folder. It contains Git's internal data such as history, branches, configuration, and staging information.



\## Question 3

Git offered to track README.md and week02/. Week01 did not appear because Git tracks files, not empty folders.



\## Question 4

After creating .gitignore, files matching the ignore rules would no longer appear in Git status. This keeps generated files such as virtual environments and Python cache files out of the repository.



\## Question 5

.gitignore should be committed because it shares the project’s ignore rules with anyone who clones the repository. It should not be ignored because it is useful project configuration.



\## Question 6

README.md moved from Untracked files to Changes to be committed. It moved from the working directory into Git’s staging area.



\## Question 7

Git printed a commit summary after the first commit, including the number of files changed. My terminal’s exact number of changed files was: \[write your number here].



\## Question 8

The first seven characters of a commit hash are the abbreviated commit ID. They are used to identify and refer to a specific commit.

