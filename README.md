# BUAA-ppt

按个人科研汇报模板制作 PPT 的 Codex 技能，支持逐页规划、原理框图与论文公式排版。

## 安装

下载并解压本仓库，将包含 `SKILL.md` 的目录命名为 `personal-ppt`，放到 `~/.codex/skills/`。安装后的文件路径应为 `~/.codex/skills/personal-ppt/SKILL.md`。

## 使用

在 Codex 中附上素材，并说明受众、汇报时长或目标页数。例如：

> 用我的PPT制作助手，根据这份实验报告规划一个 10 分钟的组会汇报。先给我看提纲和每页要讲的重点。

确认方案后，告诉助手“按这个方案制作 PPT”。也可以直接用 `$personal-ppt` 指定此技能。

## 模板与素材

- [版式规范](references/house-style.md)规定封面、编号提纲、章节切换和正文布局。每张正文页用页首要点说明重点，页底用一句话总结结论。
- [表格示例](references/table-colors.png)和[原理框图示例](references/principle-diagram.png)分别用于对照配色和技术流程。框图可结合真实观测、结构示意和公式，缺少合适插图时可用 Image2 补充示意图。
- [制作规则](SKILL.md)包括论文公式排版和 Times New Roman 字体要求。[致谢页模板](assets/template-closing.pptx)可直接复制到新汇报末页。
