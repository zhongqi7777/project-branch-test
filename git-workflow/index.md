## git search branch in all branch 
git branch --all | grep branchname


## git search branch in only remote  branch 
git branch --r | grep branchname


## view all branch relation  查看branch 之间关系
git log --graph --all --decorate --simplify-by-decoration --oneline


## update remote branch list

git remote update origin --prune

git remote update origin -p
