# Welcome to this Demo!

pushing: 
git status, git add ., git commit -m "title" -m "description", git push

some text etc:
Commands
- clone: copy a repository into your local environment
- Add: track files and changes
- Commit: save files to Git
- Push: upload commits to a remote repo, github
- Pull: opposite of push, pull code from remote repo
- ls -la: list all files, including hidden ones
- git status: shows all files created, updated, deleted but haven't been saved
- git add: tell which file to track changes
- git add . = track all files that is shown in git status
Initializing github repo from local
- git init: initializes git for a repository
- git remote -v: show all git repos connected
- git push -u origin master: set default "git push"

commiting from command line in terminal example:
git commit -m "commiting from VSCode to learn; index.html" -m "description"

making commits live on github, pushing:
Preliminary
- need to make an ssh key
- key.pub <- public key to share to people
- pushing code to github = use private key to show that you created the public key
- copying .pub key to clipboard: pbcopy < ~/.ssh/id_ed25519.pub
- SSH Keys: https://help.github.com/en/github/aut...

git push origin master: 
origin= location of git repository
master= branch to push to


First file: README.md (markdown)
#= main header
##= subheader

GitHub Workflow:
commit changes, pull request
no need to add, just commit changes
optionally pull request 
Local Git Workflow:
git add, git commit, git push, pull request

Git Branching:
- branch- copy of the repository or certain parts, each are independent to changes from other branches
- Master branch- default branch of the entire repository
- useful for testing, adding features without messing up everything
- feature branch- branch to implement a feature
- hot fix branch- quick fix on bugs

- git branch: show how many branches
- git checkout name: switch branches
- git checkout -b name/ticketnumber: new branch
- git diff name: shows changes

whenever you add, commit in a branch it stay all in that branch



## Subheader Poggers

Local development
1. open index.html