对象类型
blob
tree
commit
tag



mode        644   755  可执行位
reference   
submodules  
patch       补丁
explicitly  git diff -M
signature   git cat-file
light weight tags  refs/tags/ 



对象模型
blob  仅只是文件  可以没有内容
tree  对象  对象名 != 文件名
commit      每一次change修改，由比较得出   每一个目录都会有一个tree 指向最更根处的tree
标签对象
git tag 



GIT目录与工作目录
.git  tree -L 1
所有历史+元信息
4个
HEAD 当前分支
config 项目配置
description 描述
index 索引文件

4个
hooks/默认的钩子脚本目录
logs/各个refs的历史信息
object/所有的对象
refs/每个分支指向哪个提交

工作目录
临时的 checkout 签出文件 当前分支

Git 索引
工作目录  项目仓库 的暂存区 staging area
commit 提交 index 的内容
git status 查看索引 untracked 未被跟踪的



Git安装
git config [--global] user.name ""
git config [--global] user.email ""

git clone 
git commit -a
git diff
gitk
git branch -d -D 
git merge
git checkout
git reset --hard HEAD
git reset --hard ORIG_HEAD

git log -p -stat --pretty=oneline,short






