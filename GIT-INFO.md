
# Remove .DS_Store file from repository

## Remove existing .DS_Store files from the repository

> find . -name .DS_Store -print0 | xargs -0 git rm -f --ignore-unmatch

## Add this to the .gitignore

> .DS_Store

