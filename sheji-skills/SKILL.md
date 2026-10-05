---
name: "sheji-skills"
description: "设计技能合集：15个前端审美、图标、组件Skills的安装清单与场景路由。适用于支持 skills add 的 Codex / Cursor / Vibe Coding。当用户要美化页面、设计图标、找配色组件方案时触发。"
---

# 设计技能合集 (sheji-skills)

## Purpose

收录 15 个开源设计 Skills，提供一键安装命令与场景化推荐。避免一次性全量加载占用上下文，按需分批安装。

## Workflow

1. 确认用户场景（做页面 / 做图标 / 写文档 / 画Logo）。
2. 按下方"场景路由"推荐对应的 skill 组合。
3. 给出 `skills add` 安装命令。
4. 提醒分批安装，不要一次全装。

## 场景路由

| 场景 | 推荐组合 |
|---|---|
| 前端页面美化 | Taste Skill + Impeccable + shadcn/ui + Radix Colors |
| 交互动画页面 | 上述 + Motion AI Kit |
| App/界面图标 | Better Icons |
| Logo品牌设计 | minimal-logo-design-skill（单独用） |
| 文档、架构图、徽章 | Mermaid + Markdown Badges |
| 配色方案 | Radix Colors |
| 字体 | Fontsource |

## Skill 清单

### 一、前端审美（6个）

1. **Impeccable** — 通用前端审美
   `skills add https://github.com/max-long/impeccable`
   何时调用：页面整体看起来"土"、"廉价"、配色布局不协调时。做任何前端页面的第一选择。
2. **Taste Skill** — 品味调优
   `skills add https://github.com/max-long/taste-skill`
   何时调用：页面功能都对，但缺"高级感"，想提升细节质感（间距、字重、留白）时。与Impeccable搭配使用。
3. **UI Skills** — UI组件审美
   `skills add https://github.com/max-long/ui-skills`
   何时调用：需要设计按钮、卡片、表单、弹窗等具体组件样式时。
4. **Motion AI Kit** — 动效
   `skills add https://github.com/max-long/motion-ai-kit`
   何时调用：页面需要过渡动画、加载动效、交互反馈（hover、点击效果）时。静态页面不需要。
5. **Better Icons** — 图标设计
   `skills add https://github.com/max-long/better-icons`
   何时调用：需要原创App图标、界面小图标，且现有图标库找不到合适的时。
6. **DESIGN.md** — 设计规范
   `skills add https://github.com/max-long/design-md`
   何时调用：项目需要统一设计语言、写设计文档、定配色/字体/间距规范时。

### 二、Logo设计（1个）

7. **minimal-logo-design-skill** — 极简Logo（梵想美学）
   `skills add https://github.com/fantasy-studio/minimal-logo-design-skill`
   何时调用：需要设计品牌Logo，且风格偏向极简、东方美学时。单独使用，不与前端组混装。

### 三、素材组件库（8个）

8. **Rough.js** — 手绘风图形
   `skills add https://github.com/rough-stuff/rough`
   何时调用：需要手绘风格的图表、示意图、标注时。正式商务页面不适用。
9. **shadcn/ui** — React组件库
   `skills add https://github.com/shadcn-ui/ui`
   何时调用：用React开发，需要现成的按钮、表格、对话框等组件时。非React项目不适用。
10. **Radix Colors** — 配色系统
    `skills add https://github.com/radix-ui/colors`
    何时调用：需要选配色、定主题色、做深浅色模式时。与Impeccable搭配效果好。
11. **README Stats** — GitHub统计卡片
    `skills add https://github.com/anuraghazra/github-readme-stats`
    何时调用：写项目README，需要展示GitHub统计徽章时。仅用于文档美化。
12. **Mermaid** — 图表
    `skills add https://github.com/mermaid-js/mermaid`
    何时调用：需要画流程图、时序图、架构图、甘特图时。用代码生成图表，比手画快。
13. **Simple Icons** — 品牌图标库
    `skills add https://github.com/simple-icons/simple-icons`
    何时调用：需要展示第三方品牌图标（如GitHub、微信、支付宝 logo）时。直接引用，不用自己画。
14. **Fontsource** — 字体
    `skills add https://github.com/fontsource/fontsource`
    何时调用：需要引入特定字体（尤其是Google Fonts的npm版本）时。做中文页面主要用系统字体，这个用得少。
15. **Markdown Badges** — 徽章
    `skills add https://github.com/Ileriayo/markdown-badges`
    何时调用：写README需要技术栈徽章（如"React"、"MIT"小徽章）时。仅用于文档美化。

## Operating Rules

1. 分批安装：做UI页面时只加载前端审美组；做Logo单独加载minimal-logo；写文档再加载第三组。
2. 校验安装：`skills list` 查看已加载的全部skill。
3. 不要一次性安装全部15个，会占用大量上下文。
4. 详细说明见 `references/`。
