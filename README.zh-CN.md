<div align="center">

# Craft Data Story Charts

**一套完整、与软件无关的方法：把已经形成的数据发现，转化为受众的理解、决策或行动。**

[![License: MIT](https://img.shields.io/badge/License-MIT-172B4D.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-compatible-246BFD.svg)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-install-246BFD.svg)](https://skills.sh/NINTING/craft-data-story-charts)

[English](README.md) · [简体中文](README.zh-CN.md) · [示例画廊](#示例画廊) · [Skill](skills/craft-data-story-charts/SKILL.md)

</div>

![带有上游反馈回路的完整数据故事流程](examples/28-complete-workflow-feedback-loop.png)

## 它是一套完整转换，不是图表工具箱

制图软件能够画出标记，但不能替你决定：这位受众究竟需要理解什么、哪些证据已经足够、注意力应该先后落在哪里、文字与视觉如何共同解释，以及沟通最终要促成什么反应。

这个 Skill 把一个沟通意图贯穿到底：

```text
分析结果
→ 受众与期望反应
→ 中心思想与证据
→ 视觉编码
→ 降低认知负荷
→ 引导注意力
→ 可用的设计
→ 叙事顺序
→ 经受众检验的实际成图
```

图表类型、颜色、文字、标签、填充、阴影、边框、注释、动画和布局，不是互不相干的技巧；它们只在能够推动同一个沟通意图时才被采用。

Skill 不限定 Matplotlib、D3、ECharts、Vega、Excel、Tableau、Power BI，也不限定任何编程语言。

## Skill 会让 Agent 完成什么

- 区分探索性分析与解释性结果；
- 明确受众、期望反应、交付媒介、既有认知与可能顾虑；
- 把结果压缩成“三分钟故事”和一句完整的中心思想；
- 只选择必要证据、上下文、不确定性和会改变决策的反面证据；
- 根据受众需要完成的比较选择图表，而不是接受软件默认形式；
- 删除无用元素、弱化必要背景、只强调承载结论的证据；
- 明确设计第一、第二、第三视觉落点；
- 把文字走向、阅读路径、颜色、填充、阴影、留白和可访问性当作可视化本身；
- 组织开端、发展和结尾，并分别适配现场讲述与独立阅读；
- 生成实际成图，检验受众理解，并回到最早出错的阶段修改。

## 安装

```bash
npx skills add NINTING/craft-data-story-charts
```

手动安装到 Codex 时，把 `skills/craft-data-story-charts` 复制到：

```text
~/.codex/skills/craft-data-story-charts/
```

Windows 通常对应 `%USERPROFILE%\.codex\skills\craft-data-story-charts\`。

## 使用

```text
使用 $craft-data-story-charts 处理这份已经形成结论的分析结果。

受众：CFO 与运营负责人。
期望反应：决定下一季度把预算投入哪项干预措施。
媒介：可以独立阅读的管理层单页。
创建一张解释性图表；保留不确定性与反面证据，实际渲染，
并执行 Skill 的完整质量门槛。
```

如果结论尚未形成，Skill 会先保持探索状态，不允许用颜色和注释把未经验证的假设伪装成结论。

## 完整方法

| 阶段 | 回答的问题 | 主要方法 |
|---|---|---|
| 1. 探索还是解释 | 结论是否已经成立？ | 保留候选解释；不删除会改变决策的证据 |
| 2. 理解上下文 | 谁需要什么、通过什么方式、为什么？ | 受众、反应、关系、媒介、语气、成功标准 |
| 3. 提炼中心思想 | 最完整而简洁的核心信息是什么？ | 三分钟故事、中心句、低成本故事板 |
| 4. 证据与图表 | 受众必须完成什么比较？ | 证据分层、诚实编码、与最近替代方案比较 |
| 5. 降低认知负荷 | 什么应当删除或后退？ | 格式塔、直接标签、删除 → 弱化 → 强调 |
| 6. 聚焦注意力 | 第一、第二、第三眼应看哪里？ | 位置、对比、大小、字重、克制的强调色 |
| 7. 像设计师一样思考 | 受众能否使用、理解并接受？ | 可供性、文字、可访问性、美观、接受度 |
| 8. 故事与媒介 | 理解应按什么顺序展开？ | 开端—发展—结尾、标题主线、垂直逻辑、口头与书面 |
| 9. 渲染与迭代 | 真实受众是否收到预期信息？ | 实际成图、复述测试、数值核对、向上游返工 |

贯穿全程的 [Data Story Brief](skills/craft-data-story-charts/SKILL.md) 防止这些阶段退化成互不相关的检查清单。

## 覆盖的视觉方法

参考文档完整覆盖：

- 简单文本、表格、热力图、散点图、折线图、斜率图、条形图、堆叠与百分比堆叠图；
- 发散堆叠、正负贡献堆叠、瀑布图、横向优先级堆叠、面积图、饼图/环形图、双轴风险和多视图；
- 结论性标题、文字层级、阅读方向、直接标签、注释和页面位置；
- 格式塔分组、对齐、留白、边框、图例、网格线、标记点和数值精度；
- 颜色语义、有序明度、灰度冗余、可访问性和深色背景；
- 装饰阴影、结构填充、数据区间和上下文区域之间的明确区别；
- 动画、类别顺序、意大利面图的替代方案、共用尺度的小多图和受众接受度。

## 示例画廊

v2 画廊已经基于原创合成数据重新生成，共 30 张最终 PNG。它展示的是完整方法论，而不只是图表类型列表。公开仓库不附带特定示例的数据集、渲染脚本或软件复现教程。

### 上下文与完整流程

| Data Story Brief | 完整反馈回路 |
|---|---|
| [![受众优先的 Data Story Brief](examples/01-context-data-story-brief.png)](examples/01-context-data-story-brief.png) | [![完整上游流程](examples/28-complete-workflow-feedback-loop.png)](examples/28-complete-workflow-feedback-loop.png) |

### 根据受众任务选择展示形式

| 简单文本 | 精确值表格 |
|---|---|
| [![简单 KPI 文本](examples/02-simple-text-kpi.png)](examples/02-simple-text-kpi.png) | [![查询表格](examples/03-lookup-table.png)](examples/03-lookup-table.png) |

| 突出表格 / 热力图 | 散点关系 |
|---|---|
| [![突出表格热力图](examples/04-highlight-table-heatmap.png)](examples/04-highlight-table-heatmap.png) | [![散点关系](examples/05-scatter-relationship.png)](examples/05-scatter-relationship.png) |

| 突出式时间趋势 | 预测区间 |
|---|---|
| [![突出式折线趋势](examples/06-highlighted-line-trend.png)](examples/06-highlighted-line-trend.png) | [![预测区间](examples/07-forecast-interval.png)](examples/07-forecast-interval.png) |

| 前后斜率 | 排名条形图 |
|---|---|
| [![斜率图](examples/08-slope-before-after.png)](examples/08-slope-before-after.png) | [![横向排名条形图](examples/09-ranked-horizontal-bars.png)](examples/09-ranked-horizontal-bars.png) |

| 总量与构成 | 相对构成 |
|---|---|
| [![总量与构成堆叠图](examples/10-stacked-total-composition.png)](examples/10-stacked-total-composition.png) | [![百分比构成](examples/11-100pct-composition.png)](examples/11-100pct-composition.png) |

| 发散情感构成 | 正负贡献 |
|---|---|
| [![发散情感构成](examples/12-diverging-sentiment.png)](examples/12-diverging-sentiment.png) | [![正负贡献](examples/13-positive-negative-contribution.png)](examples/13-positive-negative-contribution.png) |

| 瀑布图 | 优先级堆叠 |
|---|---|
| [![瀑布贡献图](examples/14-waterfall-contribution.png)](examples/14-waterfall-contribution.png) | [![横向优先级堆叠](examples/15-horizontal-priority-stack.png)](examples/15-horizontal-priority-stack.png) |

| 分布与区间 | 按任务替代饼图 |
|---|---|
| [![分布区间](examples/16-distribution-interval.png)](examples/16-distribution-interval.png) | [![饼图替代方案](examples/17-pie-alternatives-by-task.png)](examples/17-pie-alternatives-by-task.png) |

| 双轴替代方案 | 地理与精确排名 |
|---|---|
| [![双轴替代方案](examples/18-dual-axis-alternative.png)](examples/18-dual-axis-alternative.png) | [![地图与标准化比较](examples/29-map-plus-normalized-comparison.png)](examples/29-map-plus-normalized-comparison.png) |

| 面积表达量级 | 折线表达精确变化 |
|---|---|
| [![按任务选择面积或折线](examples/30-area-versus-line-task.png)](examples/30-area-versus-line-task.png) | [![文字与阅读路径](examples/21-text-reading-path.png)](examples/21-text-reading-path.png) |

### 降低负荷并引导注意力

| 去杂乱前后 | 注意力层级 |
|---|---|
| [![去杂乱转换](examples/19-declutter-before-after.png)](examples/19-declutter-before-after.png) | [![注意力层级](examples/20-attention-hierarchy.png)](examples/20-attention-hierarchy.png) |

| 填充与阴影语义 | 密集折线转小多图 |
|---|---|
| [![填充与阴影语义](examples/22-fill-shading-semantics.png)](examples/22-fill-shading-semantics.png) | [![共用尺度小多图](examples/23-spaghetti-to-small-multiples.png)](examples/23-spaghetti-to-small-multiples.png) |

| 深色背景适配 | 冗余无障碍编码 |
|---|---|
| [![深色背景](examples/26-dark-background.png)](examples/26-dark-background.png) | [![无障碍冗余编码](examples/27-accessible-redundant-encoding.png)](examples/27-accessible-redundant-encoding.png) |

### 故事与交付

| 开端 → 发展 → 结尾 | 现场讲述与独立阅读 |
|---|---|
| [![开端发展结尾](examples/24-beginning-middle-end.png)](examples/24-beginning-middle-end.png) | [![现场与书面交付](examples/25-live-vs-self-contained.png)](examples/25-live-vs-self-contained.png) |

## 仓库结构

```text
craft-data-story-charts/
├── skills/craft-data-story-charts/
│   ├── SKILL.md
│   ├── agents/openai.yaml
│   └── references/
│       ├── end-to-end-method.md
│       ├── chart-selection.md
│       ├── visual-language.md
│       ├── story-delivery.md
│       ├── quality-gate.md
│       └── methodology-map.md
├── examples/*.png
├── README.md
├── README.zh-CN.md
├── CONTRIBUTING.md
└── LICENSE
```

## 方法来源与边界

本项目是独立的开源方法实现，主要受到 Cole Nussbaumer Knaflic 的 *Storytelling with Data* 及中文版《用数据讲故事》启发，与作者或出版社不存在隶属或背书关系。

[方法论映射](skills/craft-data-story-charts/references/methodology-map.md)把全书十章映射到完整流程，并明确区分书本方法与为 AI 生产增加的约束，例如统一状态对象、必须检查实际成图、数值完整性核对和量化质量门槛。仓库不包含书本扫描页或复刻插图。

## 参与贡献与许可证

欢迎提交 Issue 和 Pull Request，详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

[MIT](LICENSE) © 2026 NINTING
