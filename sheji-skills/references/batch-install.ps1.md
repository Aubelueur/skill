# 一键批量安装脚本（PowerShell 7）

```powershell
$skills = @(
"https://github.com/max-long/impeccable",
"https://github.com/max-long/taste-skill",
"https://github.com/max-long/ui-skills",
"https://github.com/max-long/motion-ai-kit",
"https://github.com/max-long/better-icons",
"https://github.com/max-long/design-md",
"https://github.com/fantasy-studio/minimal-logo-design-skill",
"https://github.com/rough-stuff/rough",
"https://github.com/shadcn-ui/ui",
"https://github.com/radix-ui/colors",
"https://github.com/anuraghazra/github-readme-stats",
"https://github.com/mermaid-js/mermaid",
"https://github.com/simple-icons/simple-icons",
"https://github.com/fontsource/fontsource",
"https://github.com/Ileriayo/markdown-badges"
)
foreach($s in $skills){
    skills add $s
}
```

> 注意：不推荐一次性全量安装。按场景分批加载，见 SKILL.md 中的"场景路由"。
