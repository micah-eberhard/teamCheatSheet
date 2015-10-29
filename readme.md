## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - __Fill Me Out__

#### Repo History
`$ git log` - __Fill Me Out__

`$ git log --oneline --decorate --color --graph --all` - __Fill Me Out__

`$ git log -p [filename]` __Fill Me Out__

#### Stage files to commit
`$ git add <filename>` - __Fill Me Out__

`$ git add -A` - __Fill Me Out__

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - __Stores current content in a new commit, includes a commit message which is typed inside the quotes.__

#### Branching
`$ git branch <branch name>` - __Fill Me Out__

`$ git branch` - __Fill Me Out__

`$ git checkout <branch name>` - __Fill Me Out__

#### Merging

`$ git merge <branch name>` - __Pulls in changes from the named branch (since they diverged in the first place). git pull actually uses git merge, just more specifically.__
