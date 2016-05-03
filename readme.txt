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