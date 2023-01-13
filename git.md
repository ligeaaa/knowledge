git init  （初始化）
git add  .（添加进暂存区）
git commit -m"[text]"   （添加进本地库）
git status  （查看状态）

ssh-keygen -t rsa  （生成公钥）
(对应目录C:\Users\Y\ .ssh里（Y为电脑用户名，每个人不同）用记事本打开id_rsa.pub，得到ssh key公钥)

git remote add origin 仓库地址 （关联仓库）

git push -u origin master
yes
(上传本地代码)