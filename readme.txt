把大象放到冰箱需要3步
git config --global user.name "duke"
git config --global user.email "466300686@qq.com"
一 创建版本库
命令
1） mkdir learngit  创建名字为learngit的文件夹（基于该目录下）
2） cd learngit  进入该目录
3） pwd  显示现在目录路径
4） ls -ah 显示目录下所有文件

Git命令
1） git init 初始化一个Git仓库
2）添加到Git 仓库 两步 
   1、 git add <file1> <file2> 把文件添加到仓库
   2、 git commit -m “说明” (-m是用来添加说明) 提交到仓库 
   
二 时光穿梭
 1) git status  查看git版本里面最新的动态
 2）git diff ：查看修改内容
 3) 每次修改后需要 git add  和git commit
 4) git log 查看每次修改的内容
{四部分：1 commit id 你提交的版本号；2 author：姓名 邮箱  3：日期 4：提交备注}
5） git log --pretty=oneline  可以减少内容 只显示 1和4（优美简介在一行）  
6）在git中用head表示当前版本，head^上一个版本，head^^上上个版本 或者head~100
   git reset --hard head^ 上一个版本 cat readme.txt 查看具体内容 
7） git reflog 查看命令历史，以便确定回到未来那个版本

工作区和暂存区 ：git相比svn就是存在暂存区的概念
工作去（working directory）：电脑里面看到的目录。
.git这个隐藏目录，这个不算工作区，而是git的版本库。
版本库又分为 stage暂存区 和git的分支master（head指针指向的分支）
1、git add 只是把文件修改添加到暂存区
2、gitcommit 提交更改，实际上就是把暂存区的所以内容提交到当前分支。  

000000000000000000000000000000000000000

rm -f ./.git/index.lock 删除文件
clear 清屏

git 字段add不commit 会被放在暂存区。。 git管理的是修改而不是文件
git diff head  --readme.txt

1） git checkout --file  直接丢弃工作区修改的内容
2） git reset head file 丢弃缓存区数据
3） 提交后没有推送远程库可以直接撤回到上一个版本。

