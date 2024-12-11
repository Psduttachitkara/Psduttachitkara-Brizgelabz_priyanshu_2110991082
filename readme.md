git rebase
git checkout --orphan newMain
git rm -rf
add c.txt
git status
git merge newMain --allow-unrelated-histories
git branch -d feature feature11 feature12
git branch -D feature15
git pull 
git push
git commit -m "delete"
git push

