# shisei-pose-dataset

给绘画或多模态 AI 当姿势参考用的线稿图包。图片是无脸人偶，取自 [Shisei](https://github.com/wquguru/shisei)（CC0），分类和索引由本仓库另行编制。本仓库不是 Shisei 官方项目。

## 内容

- 280 组姿势，共 1212 张 600px 线稿（webp）。同一个姿势有多个视角：正面、斜侧、侧面、俯视、仰视。
- 7 个主分类：站姿、坐姿、跪/蹲、卧姿、倒立/高难度、双人高低组合、半身手势。另有人数、全身/半身等标签。
- `poses.json`（UTF-8 索引）和 `poses.csv`（方便手动改标签）。

## 下载

去 [Releases](../../releases/latest) 下载 `shisei_penna_pose_pack_v1.zip`（约 20.9 MB）。仓库本身只放说明和许可文件。

## 注意事项

- 每个姿势的中文描述是按分类套用模板生成的，不是逐张细标。我逐个看过每个姿势的主视角，其余视角没有逐张人工复核。
- 上游 Shisei 的姿势名称、编号和分类沿用自 ai-pose-gallery，未获授权，本仓库没有使用。
- 标签 `sensitive:suggestive_series` 表示该姿势来自上游的“性感”或“双人”系列，建议默认隐藏。
- Shisei 作者请求不要用这些图表现真人、未成年人或露骨内容。这是作者的请求，不是许可条件，但请尊重。

## 许可

图片为 CC0 1.0，上游原文见 `UPSTREAM_LICENSE_images` 和 `UPSTREAM_NOTICE`。本仓库自编的分类和索引同样以 CC0 1.0 发布。
