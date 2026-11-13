# 拾光手记

这是一个使用 GitHub Pages 和 Jekyll 制作的个人资料库。发布的网站及文章是公开的，请勿上传私密信息。

## 写新文章

在 `_posts` 中创建名为 `年-月-日-英文短名称.md` 的文件，例如 `2026-11-15-my-note.md`：

```markdown
---
layout: post
title: 我的文章标题
category: 技术笔记
---

这里写文章内容。
```

分类可填 `随笔与日记`、`技术笔记` 或 `文章与资料`。提交更改后 GitHub Pages 会重新构建网站。

修改 `_config.yml` 中的 `title` 可更换站名，修改 `about.md` 可编辑个人介绍。图片放在 `assets` 目录；仓库发布在子路径时，在文章中用 `{{ '/assets/图片名.png' | relative_url }}` 引用。
