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