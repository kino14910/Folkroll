---
title: 'Tailwind CSS'
description: 'Tailwind CSS 配置和使用'
published: 2024-01-28
category: '前端'
---

### 禁用css提示

VS Code 默认会对 CSS/SCSS 文件进行语法验证。你可以通过设置关闭对 `@apply` 的警告：

1. 打开 VS Code 设置（`Ctrl + ,` 或 `Cmd + ,`）
2. 搜索 `css.lint.unknownAtRules`
3. 将其值从 `"warning"` 改为 `"ignore"`

或者，在你的项目根目录的 `.vscode/settings.json` 中添加：

```json
{
  "css.lint.unknownAtRules": "ignore",
  "scss.lint.unknownAtRules": "ignore"
}
```

> 如果你用的是 SCSS、Less 等预处理器，也要对应设置 `scss.lint.unknownAtRules`。



