# github-3.2-jason

## What is GitHub Authentication and how & what methods are available to be implemented?
GitHub Authentication is the process of verifying your identity when accessing your account’s resources on GitHub. You can authenticate to GitHub using different credentials depending on where you authenticate 1.

Some of the methods currently available for authentication to GitHub include:

Username and password with two-factor authentication (2FA) 1
Personal access token 1
SSH key 1

You may use two-factor authentication (2FA) and SAML single sign-on, which can be required by organization and enterprise owners 1.

If you’re authenticating with the command line, you can access repositories on GitHub in two ways: HTTPS and SSH. Both have a different way of authenticating. The method of authenticating is determined based on whether you choose an HTTPS or SSH remote URL when you clone the repository

## 15 GitHub commands and what they are used for:
git init: This command initializes a new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.

git clone [url]: This command is used to obtain a repository from an existing URL.

git status: This command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven’t, and which files aren’t being tracked by Git.

git add [file or directory]: This command adds a change in the working directory to the staging area. It tells Git that you want to include updates to a particular file or directory in the next commit.

git commit -m “[commit message]”: This command captures a snapshot of the project’s currently staged changes. Committed snapshots can be thought of as “safe” versions of a project—Git will never change them unless you explicitly ask it to.

git push [repository] [branch]: This command sends local commits to the remote repository. It’s a way to synchronize your work with a team.

git pull: This command fetches the most recent changes from the remote repository that are not yet in your local version and merges them.

git branch: This command lists all local branches in the current repository.

git checkout [branch]: This command is used to switch from one branch to another.

git merge [branch]: This command merges the specified branch’s history into the current branch. It’s a way to integrate work between different branches.

git remote -v: This command shows a list of remote repositories that your local repository is configured to connect to.

git pull origin [branch]: This command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.

git push origin [branch]: This command pushes your branch to your remote repository, so others can use, review, or implement your changes.

git log: This command shows a list of all the commits made in a repository. The latest commits appear at the top.

git rm [file]: This command removes a file from your repository and also from your local file system.

## 4 GitHub commands that you think you will use the most in the real project and why
git clone [url]: This command is critical as it allows you to download a repository that exists on a remote server (like GitHub) onto your local machine. It’s typically one of the first commands you would use when joining a new project or when you want to work on an existing project from a different machine.

git pull: This command updates your local version of a repository to the latest version on the server. You’ll use this often to ensure that your local copy stays in sync with the project as other people make changes. This way, you’re always working with the latest code.

git add [file or directory] and git commit -m “[commit message]”: These commands are paired together. The git add command allows you to choose specific changes to include in your next commit, which represents a snapshot of your project. git commit then creates that snapshot, and -m lets you attach a message to your changes to describe what you’ve done. You’ll use these commands every time you’ve made changes that you want to record - whether that’s adding a feature, fixing a bug, or changing documentation.

git push [repository] [branch]: After you’ve made your changes locally and committed them with git commit, you’ll want to share those changes with your team or backup your work to a remote server. This is where git push comes in. It sends your commits to the remote repository so others can access them and they’re safely stored off your local machine.

References
Bing chat
ChatGPT