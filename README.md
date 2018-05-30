# xiao-git
learning git

总结一下多人协作的git开发流程

1. 自已checkout自已的一个分支，每次准备修改代码之前都 git pull --rebase 拉取远程master上面的代码并合并，有冲突需要解决

2. 自己在自己的代码上面修改

3. 一个feature测试完成，已经确定没有问题的时候。checkout到master分支，git pull --rebase 拉取远程master

4. git merge mybranch 把开发的分支合并到master，有冲突解决

5. 推送自己的修改到远程分支
