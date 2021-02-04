## git search branch in all branch 
git branch --all | grep branchname


## git search branch in only remote  branch 
git branch --r | grep branchname


## view all branch relation  查看branch 之间关系
git log --graph --all --decorate --simplify-by-decoration --oneline


## update remote branch list

git remote update origin --prune

git remote update origin -p


## tag

### view tag list
git tag 

### create tag
git tag -a <tagname> -m" v1.1.1"

### push remote

git push origin --tags

### delete local tag
git tag -d <tagname>

### delete remote tag

git push origin :refs/tags/<tagname>


### view remote tags
git ls-remote --tags


## git rebase 成功之后撤销操作 master dev


git reflog 

git reset --hard 

 




