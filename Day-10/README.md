# Day 10 - Clone, Fork & Collaboration

## What I Learned
- git clone downloads a full copy of a repository with its history
- What a fork is, and why it's needed (discovered by trying to edit a repo I didn't own)
- GitHub automatically directs changes to a fork when write access is missing
- Remote-tracking branches (git branch -a) and switching to one locally

## Commands Practiced
- git clone <url>
- git branch -a
- git switch <remote-branch-name>
- git remote -v

## Key Takeaway
Trying to edit a repository I don't have write access to showed exactly why forks exist - GitHub redirects the change to my own copy instead of blocking it entirely. Cloning my fork brought that entire history, including branches like patch-1, onto my computer.
