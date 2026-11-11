# my-superagent

这是给 **dsh-superagent** 练手用的沙箱仓库。

## 怎么给它派活

在这个仓库里开一个 **Issue**，或者在某条评论里写：

```
@tianya3107 <你要它做的事>
```

它会：
1. 在一分钟内出现在 Superagent 面板的概览里（变成一个 Ticket）
2. 用自己的 Session 和目录干活
3. 开 `agent/` 前缀的分支、提 PR
4. 回到原 Issue 里回话

## 几条规矩

- **只认允许名单上的人**：目前只有 `13866212855` 的请求会受理，其他人 @ 它一律不理。
- **不会自动合并**：PR 提出来等人看、人点合并。
- **提交署名**：所有 commit 用 `tianya3107` 身份，一眼能看出是它干的。
- **先窄后宽**：先在这个沙箱里看它靠不靠谱，再考虑指向正经项目。

## 目录约定

- 每个 Ticket 在独立的 git worktree 里工作：`agent/<ticket 名>` 分支
- 本地 clone：`D:\user\my-superagent`（WSL 里是 `/mnt/d/user/my-superagent`）

---
维护：刘家阳 · 建于 2026-11
