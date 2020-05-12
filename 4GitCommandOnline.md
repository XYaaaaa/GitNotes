代码要先提交到本地仓库再提交线上仓库
1.Use Clone Command:
    git clone 线上仓库地址

2.提交到线上仓库:
    git add .
    git commit -m "提交到本地仓库"
    git push (这个指令就是把代码从本地仓库push到线上仓库)
    注意，如果push后返回了403，则需要用editor打开.git文件夹的config文件，将[remote "origin"]下的 url=https://github.com/XYaaaaa/test.git 改成
    url=https://用户名:密码@github.com/XYaaaaa/test.git

3.拉取线上仓库的最新版本:
    git pull 