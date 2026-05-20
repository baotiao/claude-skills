---
name: baotiao-blog
description: |
  Write or edit a blog post for Baotiao's blog (baotiao.github.io), or a
  technical note in his Markdown directory. Captures his established writing
  style: heading levels, no inline bold or backticks, frontmatter format, file
  locations, and tone. Use when asked to "写一篇博客", "发到我的博客", "写个笔记",
  "改这篇文章", or anytime producing a Markdown article/note for Baotiao.
---

# Baotiao Blog

Baotiao 写技术博客和笔记的风格规范. 写任何要发到他博客或存到他笔记目录的 Markdown 文章时, 严格按这里的规则.

## 文件位置

- 博客文章: `/Users/baotiao/git/baotiao/_posts/` — Jekyll 博客 (baotiao.github.io), 文件名格式 `YYYY-MM-DD-slug.md`, slug 用英文小写连字符.
- 本地笔记: `/Users/baotiao/Documents/Markdown/current/` — 纯 Markdown, 文件名可用中文.

博客和笔记用同一套写作风格. 唯一区别是博客有 frontmatter, 笔记没有.

## Frontmatter (仅博客)

博客文章开头用这个格式, 注意开头 `---` 后和结尾 `---` 前各有一个空行:

```
---

layout: post
title: 文章标题
summary: 一两句话说明这篇讲什么.

---
```

笔记不用 frontmatter, 标题直接用一行 `#` 标题.

## 标题层级

- 主章节标题用 `####` (四个井号).
- 子章节标题用**加粗行** (单独一行的 `**子标题**`), 不要用 `#####`.
- 绝不使用 `######`, 也不要用 `##` 或 `###`.
- 博客文章标题写在 frontmatter 的 `title:` 里; 笔记标题用顶部一行 `#`.

## 加粗

- 加粗只用于子章节标题 (单独成行).
- 不要在段落里给词语随意加粗做强调.
- 不要给列表项的开头术语加粗.
- 不要在表格单元格里加粗.

## 反引号

- 不要用行内反引号. 代码标识符 / 函数名 / 文件路径 / 变量名一律写成普通文字 (例如写 t_data, 不写带反引号的版本).
- 三个反引号的代码块可以用 — 用于真正的代码或结构化的伪代码 / 流程.

## 标点

- 中文里所有标点用英文标点 (`,` `.` `:` `;` `(` `)` 等), 不用全角标点.
- 标点符号后面加一个空格.

## 语气和内容

- 读者是资深数据库内核工程师, 平实、技术、平等对话的语气.
- 不用 AI 味的词、不用营销腔、不堆形容词.
- 简洁. 不要为了让文章"看起来像一篇完整博客"而加填充内容.
- 不要超出用户要求的范围加章节. 用户口述提纲时按提纲走, 不自己加内容.
- 用户说"篇幅不要太长"就保持短.
- 不用 emoji.

## 工作方式

- 用户口述提纲或要点时, 严格按他说的结构和内容写, 不擅自扩展.
- 用户让改某篇文章, 只改他指出的地方, 不顺手"优化"其他部分.
- 同一篇内容如果既要发博客又要存笔记, 两份正文保持一致, 只有 frontmatter 不同.
