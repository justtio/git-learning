# git-learning
## Summary of git basic uses
1. `git init`: 文件初始化。
2. `git status`: 文件状态检查，看是否有文件经过修改或者需要提交。
3. `git add <filename> | .`: 将文件加入与提交状态, `.`将所有编辑文件都放入预提交区。
4. `git commit -m “ ”`: 提交文件并添加相关信息。
5. `git branch -a`: 显示所有分支。
6. `git checkout`: 转换当前分支
7. `git checkout -b`: 建立新的分支。
8. `git log | log --oneline`: 显示变更及相关信息。
9. `git merge {branch}: 将分支并入主干
10. `git push URL master`: 将本地repo共享至github
11. `git remote add orgin URL` | `git push origin master`: 设置一个别名，便于远程和本地同步。
12. `git pull origin`:从远程同步至本地。
13. `git clone URL`: 从GitHub上获取repo。
14. `git branch -d | -D`:删除创建的分支 _但无法删除主干_。
15. `rm -rf .git`: 删除当前repo。
