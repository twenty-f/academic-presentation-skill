# 学术 PPT Skill · Codex 试用包（含动画素材）

下载或克隆这个公开仓库，用 Codex 打开下载目录。保留 `academic-presentation-skill/` 整个目录，里面的 `SKILL.md` 是入口，参考说明按相对路径读取。直接读取即可使用这套工作流程。

## 第一次试用

在 Codex 打开解压后能看到本 README 和 `academic-presentation-skill/` 的目录，粘贴这一句。

> 请使用 `academic-presentation-skill/SKILL.md`。

初次启动时，选「引导式试用」就用包内虚构案例，选「直接开始」就接着提供自己的材料和任务。选择记录只保存在本地试用包里。在 Codex 的新聊天中继续打开同一个可写目录，即可跳过开场选择。随时可以说「重新看引导」，再次使用虚构案例。

## 用于自己的论文或已有 PPT

把自己的论文 PDF、可用的研究笔记或 PPTX 放进 Codex 能读取的位置，发下面这段并替换方括号中的内容。

> 请读取 `academic-presentation-skill/SKILL.md` 并按相关参考执行。使用我提供的 [论文 PDF／研究笔记／已有 PPTX]，为 [听众] 用 [时长] 讲清 [本次重点]。用 [语言] 编写可编辑 PPTX 和逐页讲者备注，注明实际采用的数据口径及出处。若是改稿，先核对我指定的底稿版本和受影响页面，再按本轮范围另存。目标放映软件是 [PowerPoint／WPS／暂未确定]。交付时给出文件路径和实测范围。

本包提供通用工作说明、表单、虚构样例和离线动画素材。实际制作、渲染和放映验证取决于接收方环境已有的能力。可以先在当前项目按路径使用。出现问题时，反馈操作系统、Codex 使用方式、卡住的步骤和实际报错，隐去个人路径和研究材料。

## 动画资源与参考项目

[动画资源指南](academic-presentation-skill/references/animation-library.md)包含原仓参考静帧、组件索引与素材适用场景。16 组 SVG／PNG 组件和 5 张获准免费转发的原版 JPEG 已随仓库提供，离线即可打开。参考静帧用于观察构图，原生逐击效果需在 PowerPoint 或兼容的制作工具中实现。

按中英文关键词查找 18 个用法，见[动画关键词索引](academic-presentation-skill/references/animation-keywords.csv)。也可以直接选一份带虚构数据和静态备用方案的完整分镜：[条件分支](academic-presentation-skill/examples/animation/branch-and-handoff.md)、[消融对比](academic-presentation-skill/examples/animation/same-scale-ablation.md)、[证据定位](academic-presentation-skill/examples/animation/evidence-localization.md)。

> 动画试跑：请读动画资源指南。在关键词索引里查「条件分支」「消融」「证据」，分别打开命中的分镜和虚构试跑数据。检查首态、每次点击的变化和静态终态。使用已有演示文稿工具时输出可编辑的试跑稿，并说明实际测试的是模拟点击、静态渲染，还是 PowerPoint／WPS 原生放映。

- [fy-code-animation · 固定版本](https://github.com/Akillll-DuoHe/fy-code-animation/tree/d9a545afa393b2ffab4f36e87371691daf8e502c) 提供分镜、动作和验收方法参考。
- [code-animation-prompts · 固定版本](https://github.com/XiaoyeCodes/code-animation-prompts/tree/2e6396abb45c2d183e91bc5a6583597411860217) 提供风格与静帧参考。原素材整理者为俯仰观照，仓库封装由 XiaoyeCodes 维护。转发参考图时保留[来源和许可说明](academic-presentation-skill/assets/animation/reference-stills/SOURCES.md)。
