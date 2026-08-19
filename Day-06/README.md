# Day 06 - Professional Git Workflow

## What I Learned
- .gitignore excludes specific files/folders from being tracked by Git
- Selective staging (git add <folder>) vs git add . 
- Git only commits what is intentionally staged

## Commands Practiced
- echo "filename" > .gitignore
- git add .gitignore
- git add Day-06/ (selective staging)
- git status
- git commit -m
- git push

## Key Takeaway
git add . stages everything, which can accidentally mix unrelated files into one commit. Selective staging (adding specific files/folders) gives full control over what actually goes into each commit.
