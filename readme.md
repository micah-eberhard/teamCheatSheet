## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - This will show the difference between what you have and what is staged (added with git add; they are also referred to as the INDEX). Using just 'git diff' shows a short description of files changed, but a filepath can also be designated.

#### Repo History
`$ git log` - __Fill Me Out__

`$ git log --oneline --decorate --color --graph --all` - __Fill Me Out__

`$ git log -p [filename]` __Fill Me Out__

#### Stage files to commit
`$ git add <filename>` - This command STAGES the files to be committed. If you want to remove a file that you have added, use: git reset <file>    This removes it without changing the other staged files.

`$ git add -A` - This adds all the files in the local repo to the staging area. Make sure to use a capital A and not a lowercase a.

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - __Stores current content in a new commit, includes a commit message which is typed inside the quotes.__

#### Branching
`$ git branch <branch name>` - Starts a new branch based on the current branch with <branch name>.

`$ git branch` - Gets a list of existing branches and highlights the current one.

`$ git checkout <branch name>` - Creates a new branch with <branch name> and also switches the working tree to the new branch.

#### Merging

`$ git merge <branch name>` - __Pulls in changes from the named branch (since they diverged in the first place). git pull actually uses git merge, just more specifically.__
