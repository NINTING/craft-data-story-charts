<div align="center">

# Craft Data Story Charts

**一套完整、与软件无关的方法：把已经形成的数据发现，转化为受众的理解、决策或行动。**

[![License: MIT](https://img.shields.io/badge/License-MIT-172B4D.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-compatible-246BFD.svg)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-install-246BFD.svg)](https://skills.sh/NINTING/craft-data-story-charts)

[English](README.md) · [简体中文](README.zh-CN.md) · [示例画廊](#示例画廊) · [Skill](skills/craft-data-story-charts/SKILL.md)

</div>

![突出关键趋势、能够独立支持决策的数据故事图](examples/04-highlighted-line-delivery.png)

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

仓库刻意只放原创的最终图片，不附加特定图表的数据集、渲染脚本或软件复现教程。

| KPI 与趋势线 | 排名比较 |
|---|---|
| [![留存率 KPI](examples/01-kpi-retention.png)](examples/01-kpi-retention.png) | [![获客成本排名](examples/02-ranked-bars-cac.png)](examples/02-ranked-bars-cac.png) |

| 目标比较 | 预测与不确定区间 |
|---|---|
| [![制造质量目标点图](examples/03-target-dotplot-defects.png)](examples/03-target-dotplot-defects.png) | [![容量预测](examples/10-forecast-capacity.png)](examples/10-forecast-capacity.png) |

| 前后变化 | 发散构成 |
|---|---|
| [![Onboarding 斜率图](examples/05-slope-onboarding.png)](examples/05-slope-onboarding.png) | [![员工满意度构成](examples/06-diverging-satisfaction.png)](examples/06-diverging-satisfaction.png) |

| 贡献变化 | 关系与异常点 |
|---|---|
| [![ARR 瀑布图](examples/07-waterfall-arr.png)](examples/07-waterfall-arr.png) | [![门店异常散点图](examples/08-scatter-stores.png)](examples/08-scatter-stores.png) |

| 密集模式 | 突出式时间趋势 |
|---|---|
| [![客服需求热力图](examples/09-heatmap-support.png)](examples/09-heatmap-support.png) | [![区域配送趋势](examples/04-highlighted-line-delivery.png)](examples/04-highlighted-line-delivery.png) |

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
