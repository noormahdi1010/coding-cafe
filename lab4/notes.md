# Lab 4 Notes



## Question 1

`--global` applies the Git name and email setting to every repository on this computer. Without it, the setting would apply only to the current repository.



## Question 2

`ls -Force` showed the hidden `.git` folder. It contains Git's internal data such as history, branches, configuration, and staging information.



## Question 3

Git offered to track README.md and week02/. Week01 did not appear because Git tracks files, not empty folders.



## Question 4

After creating .gitignore, files matching the ignore rules would no longer appear in Git status. This keeps generated files such as virtual environments and Python cache files out of the repository.



## Question 5

.gitignore should be committed because it shares the project’s ignore rules with anyone who clones the repository. It should not be ignored because it is useful project configuration.



## Question 6

README.md moved from Untracked files to Changes to be committed. It moved from the working directory into Git’s staging area.



## Question 7

Git printed a commit summary after the first commit, including the number of files changed. My terminal said 3 files changed in the first commit.


## Question 8

The first seven characters of a commit hash are the abbreviated commit ID. They are used to identify and refer to a specific commit.

## Question 9

The four-step Git loop is: edit files, check the status, stage the changes with `git add`, and save them with `git commit`. This creates a clear history of small pieces of work.

## Question 10

README.md is a standard project introduction file placed at the repository root. GitHub recognizes it automatically and renders it on the repository’s front page for visitors.

## Question 11

GitHub CLI was not installed on my computer, so I used Git Credential Manager through the browser authentication prompt when I pushed. It securely saved my GitHub authorization, so Git can authenticate future pushes without repeatedly asking for my password.

## Question 12

The root README.md file appears on the repository front page as formatted text. GitHub recognizes README files and automatically renders Markdown to introduce the project.

## Question 13

Pushing did not change my local commit history. It uploaded my existing local commits to the GitHub repository and set my local main branch to track origin/main.

## Question 14

A private repository exists online on GitHub, but only the owner and invited collaborators can access it. A repository that does not exist on GitHub has no online URL, remote backup, or collaborator access.

