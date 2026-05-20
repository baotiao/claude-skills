# claude-skills

我自己用的 Claude Code skills.

## skills

- **baotiao-blog** — 写技术博客和笔记的风格规范. 包括文件位置、frontmatter 格式、标题层级、加粗与反引号的使用约束、标点和语气. 写要发到博客 (baotiao.github.io) 或本地笔记的 Markdown 文章时使用.

## 用法

把对应 skill 目录放到 `~/.claude/skills/` 下即可:

```
cp -r baotiao-blog ~/.claude/skills/
```

之后在 Claude Code 里用 `/baotiao-blog` 调用, 或让它根据描述自动匹配.
