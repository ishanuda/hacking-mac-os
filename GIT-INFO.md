### [Back](README.md)

# This file contains the git infomations
## Lets get familiar wtih the git

## Edit global configuration file

> git config --global --edit

## Edit global user info

> git config --global user.name <User Name>

> git config --global user.email <user@email.com>

## Remove .DS_Store file from repository

### Remove existing .DS_Store files from the repository

> find . -name .DS_Store -print0 | xargs -0 git rm -f --ignore-unmatch

### Add this to the .gitignore

> .DS_Store

> git add .gitignore

> git commit -m 'commit message'


