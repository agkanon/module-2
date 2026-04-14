## 🎯 Assignment on module 2.
- All commands used
```bash
git init
touch README.md
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/agkanon/module-2.git
git push -u origin main
git branch
git checkout -b main
git checkout -b develop
git checkout -b feature/login
git push -u origin develop
git push -u origin feature/login
git checkout -b feature/payment
git checkout -b feature/profile
git checkout -b bugfix/login-error
git checkout develop
git merge feature/payment
git checkout feature/profile
git rebase develop
git checkout feature/login
touch file1.txt
git add file1.txt
git commit -m "Added file1.txt"
touch file2.txt
git add file2.txt
git commit -m "Added file2.txt"
touch file3.txt
git add file3.txt
git commit -m "Added file3.txt"
touch file4.txt
git add file4.txt
git commit -m "Added file4.txt"
touch file5.txt
git add file5.txt
git commit -m "Added file5.txt"
git log --oneline
git rebase -i HEAD~5
```
- branching screnshot
  https://ibb.co.com/ds2hc6qD

- commits
  https://ibb.co.com/VW8XT9zZ
  
### Merge vs Rebase
- Merge: Combines two branches but keeps their histories.
- Rebase: Rewrites commit history to create a linear progression.

### Squash & Reword
- Squash: Merges several commits into one.
- Reword: Changes the commit message of a commit during rebase.
