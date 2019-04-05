2019/04/05 git整理

小结
要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；
关联后，使用命令git push -u origin master第一次推送master分支的所有内容；
此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；
分布式版本系统的最大好处之一是在本地工作完全不需要考虑远程库的存在，也就是有没有联网都可以正常工作，而SVN在没有联网的时候是拒绝干活的！当有网络的时候，再把本地提交推送一下就完成了同步，真是太方便了！

git checkout -- [filename]
恢复工作区到最近一次修改的版本，但是你会丢失你 最近一次提交后你修改的内容

my stupid boss still use svn

git add
git commit -m "注释"

git status //查看git仓库当前状态
git diff //查看difference

git reflog//查看命令历史

Git和其他版本控制系统如SVN的一个不同之处就是有暂存区的概念

就是你在电脑里能看到的目录，比如我的learngit文件夹就是一个工作区

工作区有一个隐藏目录.git，这个不算工作区，而是Git的版本库。

Git的版本库里存了很多东西，其中最重要的就是称为stage（或者叫index）的暂存区，还有Git为我们自动创建的第一个分支master，以及指向master的一个指针叫HEAD




