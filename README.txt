
git config --gloal username = xxx
git config --gloal email = "xxx@email.com"
git init 

git add ./* 

git commit -m "[type] messages"

git pull 拉取


git push -u -origin main  -u 指定默认分支，以后提交不需要后面参数


git status 文件变动

git  diff  对比文件


git  reset --hard HEAD^ HEAD^^ HEAD~ HEAD~1 HEAD~100


git checkout -b 分支名称,  git switch -c 分支名称    创建并切换分支

git branch 创建分支

git  switch 切换分支

git checkout 切换分支

git reflog 历史提交记录


git clone "git仓库地址链接" 


git checkout -- * 

git rm 文件名称

git remote add origin "远程仓库链接"

git merge dev 合并分支

git branch -d dev 删除某个分支

git log --graph 分支合并图

git stash  


git stash list


git stash -pop


git tag  "v1.2"   分支里添加标签

