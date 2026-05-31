# tmux · 终端复用器完全指南

> 横向翻页网页 PPT（单 HTML 文件），基于「电子杂志 × 电子墨水」风格制作。

## 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | PPT 主文件（v1），牛皮纸暖色主题 |
| `index-v2.html` | 改进版本（v2） |
| `index-v3.html` | 最新版本（v3） |
| `assets/motion.min.js` | 动画库依赖 |

## 打开方式

直接在浏览器中打开任一 HTML 文件即可。页面支持 **横向滑动手势** 或 **键盘方向键** 翻页。

```
open index-v3.html  # macOS
```

## 风格特征

- **字体**: Playfair Display / Noto Serif SC 衬线体，电子杂志质感
- **配色**: 🍂 牛皮纸暖色系 (`--ink: #2a1e13`, `--paper: #eedfc7`)
- **背景**: WebGL 双背景 Canvas 实现流体过渡
- **模板类型**: 章节幕封、数据大字报、图片网格、流程图等

## 内容概览

tmux 终端复用器入门完全指南，覆盖：

- 会话 / 窗口 / 窗格三层模型
- 常用快捷键与实操演示
- 配置优化（前缀键、状态栏、配色）
- 插件生态（TPM、tmux-resurrect 等）
- 生产环境最佳实践

## 技术栈

- 纯 HTML + CSS + 原生 JavaScript
- 无框架依赖（仅引入 motion.min.js 动画库）
- 响应式布局，适配 16:9 ~ 21:9 屏幕

---

🤖 Generated with [Claude Code](https://claude.com/claude-code)
