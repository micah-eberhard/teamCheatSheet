## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - __Create a new, local repository__

#### Repo Status
`$ git status` - __Check the status of your current repository and see which files have changed.__

`$ git diff` - __This will show the difference between what you have and what is staged (added with git add; they are also referred to as the INDEX). Using just 'git diff' shows a short description of files changed, but a filepath can also be designated.__

#### Repo History
`$ git log` - lists commits in local repository

`$ git log --oneline --decorate --color --graph --all` - shows all of the commits on the local repo that have a color decoration

`$ git log -p [filename]` __Fill Me Out__

#### Stage files to commit
`$ git add <filename>` - __This command STAGES the files to be committed. If you want to remove a file that you have added, use: git reset <file>    This removes it without changing the other staged files.__

`$ git add -A` - __This adds all the files in the local repo to the staging area. Make sure to use a capital A and not a lowercase a.__

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - __Stores current content in a new commit, includes a commit message which is typed inside the quotes.__

#### Branching
`$ git branch <branch name>` - __Starts a new branch based on the current branch with <branch name>.__

`$ git branch` - __Gets a list of existing branches and highlights the current one.__

`$ git checkout <branch name>` - __Creates a new branch with <branch name> and also switches the working tree to the new branch.__

#### Merging

`$ git merge <branch name>` - __Pulls in changes from the named branch (since they diverged in the first place). git pull actually uses git merge, just more specifically.__
