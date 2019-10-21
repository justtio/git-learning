# git-learning

## Summary of git basic uses

1. `git init`: 文件初始化。
2. `git status`: 文件状态检查，看是否有文件经过修改或者需要提交。
3. `git add <filename> | .`: 将文件加入与提交状态, `.`将所有编辑文件都放入预提交区。
4. `git commit -m “ ”`: 提交文件并添加相关信息。
   【git commit --amend: 修改提交信息】
5. `git branch -a`: 显示所有分支。
6. `git checkout`: 转换当前分支
7. `git checkout -b`: 建立新的分支。
8. `git log | log --oneline`: 显示变更及相关信息。
   【显示文件前后差异：git log -p】【以图表形式查看分支：git log --graph】
9. `git merge {branch}`: 将分支并入主干
   【在历史记录中明确记录该次分支合并，可加上参数 --no-ff】
10. `git push URL master`: 将本地 repo 共享至 github
11. `git remote add orgin URL` | `git push origin master`: 设置一个别名，便于远程和本地同步。
12. `git pull origin`:从远程同步至本地。
13. `git clone URL`: 从 GitHub 上获取 repo。
14. `git branch -d | -D`:删除创建的分支 _但无法删除主干_。
15. `rm -rf .git`: 删除当前 repo。
16. `git diff`: 查看更该前后的差别。
17. `git reset`: 回溯历史版本。
    【git reset --hard: 让仓库的 HEAD，暂存区，当前工作树回溯到指定状态】
18. `git reflog`: 查看当前仓库执行过的操作的日志。
19. `git rebase -i`: 压缩历史。
