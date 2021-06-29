# git使用 

## git 配置

git config -- global user.name “deng”

git config -- global user.email aaa@aa.com

git config --list 查看配置

	## git 命令

git init

git add 把文件修改添加到暂存区

git commit a.txt (-m) 把暂存区的所有内容提交到当前分支

git status (-s)

git log 

git log a.txt

git log --oneline

git log --reverse 逆向显示

git diff

git revert 还原修改

git rm a.txt 删除

git mv a11.txt a12.txt 重命名

## github 

http ssh(公钥 私钥)

ssh-keygen -t rsa 生成公钥 私钥

git remote add origin git@github.com:xxxxx/xxx.git