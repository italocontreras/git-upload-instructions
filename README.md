# git-upload-instructions

1.create repository in github with readme(default branch is main)

2.in local repository:
git init 
git status (default branch is master)
git add .
git commit -m "first commit"
git branch -m master main
git remote add origin (repository)
git pull origin main --allow-unrelated-histories
git push origin main

