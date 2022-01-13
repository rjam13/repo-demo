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

## Subheader Poggers

