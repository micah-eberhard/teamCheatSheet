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
`$ git commit -m "<commit message>"` - __Fill Me Out__

#### Branching
`$ git branch <branch name>` - __Fill Me Out__

`$ git branch` - __Fill Me Out__

`$ git checkout <branch name>` - __Fill Me Out__

#### Merging

`$ git merge <branch name>` - __Fill Me Out__
