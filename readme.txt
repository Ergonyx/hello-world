Configure Git

Check version
$ git --version

Set Name and Email
$ git config --global user.name "Your Name"
$ git confit --global user.email "you@example.com"

Quick Project Setup Example
$ mkdir hello-world  // mkdir = Make Directory "Folder Name"
$ cd hello-world // cd = Change Directory "Target"
$ ls // List the items in the current directory.
$ git init // Initialize and start tracking the folder you're in.
$ git status // Check repo status.

Add (Stage) files to update in the repo
$ git add "Filename.txt"
$ git add . // Add all changed files.

Commit changes to repo.
$ git commit - "Description of changes and/or additions."

Check difference between the file now and last commit.
$ git diff // Use Shift+Q to exit.

Set Username for GitHub account.
$ git config --global user.username "Username"

Connect local repo to GitHub remote repo.
$ git remote add origin "URL From GitHub" // Origin is the primary remote.
$ git remote set-url origin "URL From GitHub" // Sets URL for existing origin.

PUSH changes from local repo to remote repo.
$ git push origin master // Push the master local repo to origin remote repo

PULL updated files from remote repo to local repo.
$ git pull "RemoteName" "BranchName" // Pull BranchName from RemoteName.

View existing/current remote addresses.
$ git remote -v