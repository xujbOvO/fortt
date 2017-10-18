# welcome to git world! :zap:

// 分支管理
git branch -r # 查看远程分支

git branch <new_branch> # 创建新的分支

git branch -v # 查看各个分支最后提交信息

git branch --merged # 查看已经被合并到当前分支的分支

git branch --no-merged # 查看尚未被合并到当前分支的分支

git branch -d <branch> # 删除某个分支

git branch -D <branch> # 强制删除某个分支 (未被合并的分支被删除的时候需要强制)

git checkout <branch> # 切换到某个分支

git checkout -b <new_branch> # 创建新的分支，并且切换过去

git checkout -b <new_branch>.. <branch> # 基于branch创建新的new_branch

git checkout $id # 把某次历史提交记录checkout出来，但无分支信息，切换到其他分支会自动删除

git checkout $id -b <new_branch> # 把某次历史提交记录checkout出来，创建成一个分支

// 分支合并和rebase

git merge <branch> # 将branch分支合并到当前分支

git merge origin/master --no-ff # 不要Fast-Foward合并，这样可以生成merge提交
