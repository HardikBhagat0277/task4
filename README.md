# task4

!.Initialize local repo & push initial commit

git init
git add .
git commit -m "added README and base files"
git branch -M main
git remote add origin https://github.com/HardikBhagat0277/task4.git
git push -u origin main

2.created dev and feature branches

# created and push dev
git checkout -b dev
git push -u origin dev

# created a feature branch
git checkout -b feature
git push -u origin feature

3.Tags and releases

# annotated tag
git tag -a v1.0.0 -m "Release v1.0.0"
git push origin v1.0.0

Useful Git commands (cheat sheet)

git status — see changes
git add -p — stage interactively
git diff — see unstaged changes
git log --oneline --graph --decorate --all — visual history
git stash save "WIP message" / git stash pop — temporarily shelve changes
git reset --soft HEAD~1 — undo last commit but keep changes staged
git revert <commit> — safe undo (creates new commit)
git branch -d feature/add-ci — delete local branch
git push origin --delete feature/add-ci — delete remote branch
