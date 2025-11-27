# Git learnings
Some Git commands
'''
git init
git config --global --list
git config --global user.name "user_name"
git config --global user.email "email_id"
git add <filename>
git rm --cached <fielname>
git restore --staged <filename>
git commit -m "commit_message"
git restore <filename>
git status
git log
git log --pretty=oneline
git log --graph
git diff
git diff --staged
git diff --cached
git commit -a -m "filename"
git add .
git branch -M main #to create main branch
git branch branch_name
git branch -d branch_name #to delete a branch
ssh-keygen -o
git remote add origin git@github.com:user_name/repo_name.git
git push -u origin main #-u represents upstream branch
gh repo create <<repo_name>> --public --source=. --push
git remote -v
#Tagging
git tag is used to mark specific points of the repository as important. These points can be milestones, versions and releases.
Two types of tagging is available
Annotated Tags - where details of the author etc metadata will be stored
Lightweight Tags - only tag will be created
Tags are static in nature, once created they stick to that commit itself and doesn't move forward

> To check list of Tags
git tag

> To create tag - annotated
git tag -a <tag_name> -m "Tag message"
git show <tag_name> 
git tag -d <tag_name>

> Create tag for a specific commit 
git tag -a <tag_name> <commit_sha> -m "tag message"

> To push tags to remote
git push origin <tag_name> 

git branch
git branch --all
git checkout -b <branch_name>
git switch -c <branch_name>
git branch <branch_name>

git switch <branch_name>
git checkout <branch_name>

git pull origin <from_branch_name>
git merge <from_branch_name>
'''