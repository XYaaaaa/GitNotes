Command of Branch:
1.查看分支:
    git branch
    当前分支前面会有一个"*"

2.创建分支:
    git branch 分支名

3.切换分支:
    git checkout 分支名

4.删除分支:
    git branch -d 分支名

5.合并分支:
    git merge 被合并的分支名

创建了一个新分支后，切换到该分支，再用本地的git操作把代码提交到本地仓库，最后用git merge命令把其他的分支的代码合并到master上(需要先切换到master branch下操作)
然后再push到线上的master分支上