# github-3.1-cliffc2
This is for assignment 2 submission 
Github Authentication and how what methods are available to be implemented

To keep our account secure, we must authenticate before we can access certain resources on GitHub. 
When we authenticate to GitHub, we supply or confirm credentials that are unique to us to prove that 
we are exactly who we declare to be.

We can access our resources in GitHub in a variety of ways: in the browser, 
via GitHub Desktop or another desktop application, with the API, 
or via the command line. Each way of accessing GitHub supports different modes of authentication.
These methods include:

Personal access tokens: Personal access tokens (PATs) are the most common method of authentication. 
A PAT is a string of characters that identifies a user and provides access to specific resources on GitHub. 
PATs can be created and revoked by the user, making them an effective method for controlling access to 
GitHub resources.

OAuth Apps: GitHub also supports OAuth 2.0, which allows users to authorize third-party applications to 
access their GitHub resources. OAuth Apps can be public or private and require users to authenticate 
with their GitHub credentials to authorize access to their resources.

SSH keys: GitHub also supports SSH keys as an authentication method. 
SSH keys allow users to connect securely to GitHub and perform actions like cloning repositories or 
pushing code changes.

GitHub Actions: GitHub Actions is a feature that allows users to automate workflows on GitHub. 
To access this feature, users must authenticate with their GitHub credentials.

SAML Single Sign-On (SSO): GitHub also supports SAML-based SSO. 
This method allows users to authenticate with their organization's identity provider to access 
GitHub resources.

Overall, GitHub provides a range of authentication methods to ensure secure access to its resources. 
Developers can choose the method that best fits their needs and integrate it into their workflow.

20 Github commands and their usage are as follows:

git config
Usage: git config -global user.name “[name]”
Usage: git config -global user.email “[email address]”
This command sets the author name and email address respectively to be used with your commits.

git init
Usage: git init [repository name]
This command is used to start a new repository.

git clone
Usage: git clone [url]
This command is used to obtain a repository from an existing URL.

git add
Usage: git add [file]
This command adds one or more files to the staging area.

Usage: git add *
This command adds one or more to the staging area.

git commit
Usage: git commit -m “[ Type in the commit message]”
This command records or snapshots the file permanently in the version history.

Usage: git commit -a
This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

git diff
Usage: git diff
This command shows the file differences which are not yet staged.

Usage: git diff –staged
This command shows the differences between the files in the staging area and the latest version present.

Usage: git diff [first branch] [second branch]
This command shows the differences between the two branches mentioned.

git reset
Usage: git reset [file]
This command unstages the file, but it preserves the file contents.

Usage: git reset [commit]
This command undoes all the commits after the specified commit and preserves the changes locally.

Usage: git reset -hard [commit]
This command discards all history and goes back to the specified commit.

git status
Usage: git status
This command lists all the files that have to be committed.

git rm
Usage: git rm [file]
This command deletes the file from your working directory and stages the deletion.

git log
Usage: git log
This command is used to list the version history for the current branch.

Usage: git log -follow[file]
This command lists version history for a file, including the renaming of files also.

git show
Usage: git show [commit]
This command shows the metadata and content changes of the specified commit.

git tag
Usage: git tag [commitID]
This command is used to give tags to the specified commit.

git branch
Usage: git branch
This command lists all the local branches in the current repository.

Usage: git branch [branch name]
This command creates a new branch.

Usage: git branch -d [branch name]
This command deletes the feature branch.

git checkout
Usage: git checkout [branch name]
This command is used to switch from one branch to another.

Usage: git checkout -b [branch name]
This command creates a new branch and also switches to it.

git merge
Usage: git merge [branch name]
This command merges the specified branch’s history into the current branch.

git remote
Usage: git remote add [variable name] [Remote Server Link]
This command is used to connect your local repository to the remote server.

git push
Usage: git push [variable name] master
This command sends the committed changes of master branch to your remote repository.

Usage: git push -all [variable name]
This command pushes all branches to your remote repository.

Usage: git push [variable name] :[branch name]
This command sends the branch commits to your remote repository.

git pull
Usage: git pull [Repository Link]
This command fetches and merges changes on the remote server to your working directory.

git stash
Usage: git stash save
This command temporarily stores all the modified tracked files.

Usage: git stash pop
This command restores the most recently stashed files.

Usage: git stash list
This command lists all stashed changesets.

Usage: git stash drop
This command discards the most recently stashed changeset.

4 Githubs commands we use the most in our projects:

git clone: This command allows you to copy an existing repository from GitHub to your local machine. 
This is a commonly used command when you want to work on an existing project, make changes, 
and contribute back to the project.

git add: This command adds changes to the staging area in preparation for committing 
those changes to the repository. This is an important command 
when you want to track changes made to a file or set of files before committing those changes.

git commit: This command saves changes made to the repository. 
It's important to add a commit message that explains the changes made so that 
other contributors can understand the changes.

git push: This command uploads local changes to the GitHub repository, 
making them visible to other contributors. This is a key command 
when you want to share your changes with other members of your team or 
when you want to contribute changes to an existing project.

These four commands are the basic building blocks of working with Git and GitHub, 
and they are essential to collaborating with others on a project.