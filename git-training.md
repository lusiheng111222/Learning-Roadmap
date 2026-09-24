# 🧪 Git 训练任务（循序渐进）

每完成一级，就在最后打勾。所有操作都在本地仓库练习即可，不用怕搞坏。

## Level 1：本地基础（add / commit / push）
1. 进入 `Python-Learning`，修改 `README.md`（随便加一行）
2. `git add README.md`
3. `git commit -m "练习：第一次提交"`
4. `git status` 确认干净
5. `git log` 查看提交记录
- [ ] 我能独立完成 add / commit

## Level 2：远程与分支（clone / pull / branch）
1. 把本仓库推到 GitHub（见 FINISH-GUIDE.md）
2. 新建分支：`git branch dev`
3. 切换：`git switch dev`
4. 在 dev 上改点东西并提交
5. 切回 main：`git switch main`
6. `git pull` 拉取最新（多人协作时常用）
- [ ] 我能独立使用 branch / switch / pull

## Level 3：合并与冲突（merge / conflict）
1. 在 main 上改 `README.md` 第一行并提交
2. 在 dev 上改 `README.md` 同一行并提交
3. `git merge dev` —— 故意制造冲突
4. 打开冲突文件，手动解决（保留想要的内容，删除 `<<<<<<<` 标记）
5. `git add .` -> `git commit` 完成合并
- [ ] 我能解决一次合并冲突

## Level 4：开源协作（fork / pull request）
1. 在 GitHub 上 fork 一个新手友好项目（搜 `good first issue`）
2. `git clone` 你 fork 的仓库到本地
3. 新建分支、修改、提交、push
4. 在 GitHub 上发起 Pull Request 到原项目
5. 等待维护者 review / 合并
- [ ] 我发起了人生第一个 Pull Request
