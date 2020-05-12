1.check present status(查看仓库当前状态): 
    git status

2.添加到缓存区: git add 文件名:
    Explaination:
    git add 指令可以添加一个文件，也可以同时添加多个文件
    语法1: git add 文件名
    语法2: git add 文件名1 文件名2 文件名3 ......
    语法3: git add .    (这个表示把当前目录添加到缓存区中)

3.提交至版本库: git commit -m "注释内容"
    版本库就是本地仓库，在文件夹的.git文件夹下
    这段注释就是日志

4.check version(查看版本):
    git log 显示提交(commit)日志
    git log --pretty=oneline 一行一行的显示日志

5.backtracking(回退操作，回到之前的版本):
    git reset --hard 版本号 (版本号是查看版本的时候看到的哈希值)
    注意：回到过去之后，要想回到之前最新的版本的时候，就要用指令去查看历史操作，以得到最新的commit id
    git reflog
    然后再reset对应版本号就可以回到未来