git init 
mkdir "first"
touch README.md 
git add README.md
git status 
git commit -m "first commit" 
git branch "first_branch"
git checkout "first_branch"
git add README.md 
git commit -m "second commit"
git checkout master
git add README.md
git commit -m "third commit" 
git log --oneline
git add README.md
git commit -m "fourth commit"
git merge first_branch
git log
git add README.md 
git commit -m "fifth commit"
git log

