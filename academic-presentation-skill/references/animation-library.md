# PPT 动画组件、分镜与参考静帧

- [组件索引与总览](../assets/animation/components/README.md)有 16 组透明 SVG／PNG，包括箭头、条件节点、证据框、行高亮与状态标记。插入时优先用 SVG，用同名 PNG 兼容。需要逐个编辑形状时，用 PowerPoint 原生形状重画。
- [参考静帧与署名](../assets/animation/reference-stills/SOURCES.md)提供 5 张离线原版 JPEG 和 6 条额外上游静帧定位。F2 适合观察节点与关系，F1 适合观察固定坐标和标签，F3 适合观察同屏对比。
- 用[单页分镜表](../templates/animation-storyboard.md)写清首态、点击动作、口头触发句和终态；按[放映核验说明](reveal-and-playback.md)实测。

## 一个逐击例子

在虚构试跑的结果页上一直保留两轮结果、分母和单位。讲到固定顺序的局限时，用一次点击显示说明与证据框。制作工具支持原生动画时，将说明和框作为可管理的对象，用「出现」或轻量「淡入」。无法做逐击时把说明放在同页两轮结果旁。交付前检查标签、数据、说明和图形间的遮挡。

图片文件承载构图和视觉标注。点击时序、对象路径和切换由演示文稿制作工具实现。上游工程用于查阅，使用包内资源无需安装、运行或下载上游工程。

## 上游项目

- 参考 [fy-code-animation 的分镜模板](https://github.com/Akillll-DuoHe/fy-code-animation/tree/d9a545afa393b2ffab4f36e87371691daf8e502c/templates)拆分叙事节点和停顿位置，参考其 [QA 模块](https://github.com/Akillll-DuoHe/fy-code-animation/blob/d9a545afa393b2ffab4f36e87371691daf8e502c/modules/qa.md)检查首帧、关键中间态和末态。
- 在 [code-animation-prompts 风格索引](https://github.com/XiaoyeCodes/code-animation-prompts/blob/2e6396abb45c2d183e91bc5a6583597411860217/docs/STYLES.md)按编号查找更多构图；保留单张来源和链接。
