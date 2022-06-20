# Demo

first commit

# Git Configuration
git config\
git config --global user.name "username"\
git config --global user.email "email"\
git config -list

# Starting Project
git init\
git clone <ssh/http>

# Local Changes
git add <filename>\
git add .\
git commit -m "message"

# Track Changes
git status\
git show\
git diff

# Commit History
git log

# Ignoring Files
.gitignore

# Branching
git branch list\
git branch -d <branchname>\
git checkout -b <branchname>

# Merging
git merge
  
# Remote
git pull origin master\
git push origin master

# Undo Changes
git revert\
git reset -hard,-soft,--mixed
