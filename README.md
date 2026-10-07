# my-first-repo

这是我用 DeepSeek Harness 配置好 Git + GitHub 之后的第一个测试仓库。

## 目的

验证从这台机器到 GitHub 的完整链路：

1. 本地提交（`git commit`）
2. 通过 SSH 推送到 GitHub（`git push`）
3. 从 GitHub 拉取（`git pull` / `git clone`）

## 配置信息

| 项目 | 值 |
|---|---|
| GitHub 用户 | cookvv |
| 认证方式 | SSH（ed25519 密钥） |
| 密钥位置 | `~/.ssh/id_ed25519` |
| 默认分支 | main |

## 常用命令

```bash
git status              # 看改动
git add -A              # 暂存全部改动
git commit -m "说明"    # 提交
git push                # 推送到 GitHub
git log --oneline       # 看提交历史
```

## 待办

- [x] 安装 Git
- [x] 配置 SSH 密钥并添加到 GitHub
- [x] 验证 SSH 认证连通
- [ ] 完成第一次 push
