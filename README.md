git init

git add .
git commit -m init
git branch -M main
git remote add origin https://github.com/Andy-Well/new-project.git
git push -u origin main
git checkout -b development
git add .
git commit -m development
git checkout main
git merge development
git status
git push origin main
