把大象放到冰箱需要3步
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