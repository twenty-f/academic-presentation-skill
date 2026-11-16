# PPT 动画组件、分镜与参考静帧

- [组件索引与总览](../assets/animation/components/README.md)有 16 组透明 SVG／PNG，包括箭头、条件节点、证据框、行高亮与状态标记。插入时优先用 SVG，用同名 PNG 兼容。需要逐个编辑形状时，用 PowerPoint 原生形状重画。
- [参考静帧与署名](../assets/animation/reference-stills/SOURCES.md)提供 5 张离线原版 JPEG 和 6 条额外上游静帧定位。F2 适合观察节点与关系，F1 适合观察固定坐标和标签，F3 适合观察同屏对比。
- 用[单页分镜表](../templates/animation-storyboard.md)写清首态、点击动作、口头触发句和终态；按[放映核验说明](reveal-and-playback.md)实测。

## 按用途找素材与分镜

在[关键词索引 CSV](animation-keywords.csv)搜索「中文搜索词」或「中英文同义词」，例如「条件分支」「消融」「证据」「转场」或 `ROI`。CSV 为 UTF-8，单元格中的多项素材使用「｜」分隔，本地路径相对于 CSV 所在目录。先看「类别和优先级」，再打开素材或完整分镜。

| 要讲清的内容 | 完整分镜 |
| --- | --- |
| 条件分支如何决定去向，下一页怎样继续跟踪同一对象 | [条件分支与跨页承接](../examples/animation/branch-and-handoff.md) |
| 如何在统一刻度和样本口径下讲清消融差值 | [同尺度消融与读图](../examples/animation/same-scale-ablation.md) |
| 如何从原始日志定位一条证据，再局部放大解释 | [证据定位与局部放大](../examples/animation/evidence-localization.md) |

三例共用[虚构试跑数据](../examples/animation/fictional-data.md)，各自提供首态、逐击顺序、可编辑做法、静态备用和素材来源。先挑一个最接近本次讲述目标的例子，然后换成实际证据、单位和结论范围。

图片文件承载构图和视觉标注。点击时序、对象路径和切换由演示文稿制作工具实现。上游工程用于查阅，使用包内资源无需安装、运行或下载上游工程。

## 上游项目

- 参考 [fy-code-animation 的分镜模板](https://github.com/Akillll-DuoHe/fy-code-animation/tree/d9a545afa393b2ffab4f36e87371691daf8e502c/templates)拆分叙事节点和停顿位置，参考其 [QA 模块](https://github.com/Akillll-DuoHe/fy-code-animation/blob/d9a545afa393b2ffab4f36e87371691daf8e502c/modules/qa.md)检查首帧、关键中间态和末态。
- 在 [code-animation-prompts 风格索引](https://github.com/XiaoyeCodes/code-animation-prompts/blob/2e6396abb45c2d183e91bc5a6583597411860217/docs/STYLES.md)按编号查找更多构图；保留单张来源和链接。
