# 我的 Git 学习笔记
## 第一次Git实验总结
1. git add 的作用是：将工作区修改的文件加入暂存区，标记这些变更准备提交，并不会保存到本地版本库。
2. git commit 的作用是：把暂存区里已经add的变更，提交到本地Git版本库，生成一条版本记录（快照），仅保存在本地，不会自动上传GitHub。
3. git restore notes.md 的作用是：用最近一次commit的版本，覆盖工作区的notes.md，撤销工作区未add的修改，恢复文件到上一次提交状态。
4. commit 与 push 的区别是：commit是本地操作，把改动保存到本机git仓库；push是联网操作，把本地已经commit好的版本，推送到远程GitHub仓库。