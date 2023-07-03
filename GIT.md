git in // 生成一个 .git 的子目录，产生一个仓库
git status // 查看当前目录下所有的文件
git aad .  //将该目录下所有的文件提交到暂存区
git add 文件名 //将该目录下指定的文件提交暂存区

git commit -m V1.0 //版本

git log  //查看我们的提交信息

git reset –hard 对应版本的哈希值 //跳转到指定的版本
git reflog  // 查看版本跳转记录