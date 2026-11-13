# 市调全流程协作

一个面向全国大学生市场调查与分析大赛及课程调研项目的中文 AI Skill，帮助团队衔接选题、调查设计、真实预调查、数据整理、分析、报告和答辩，并保留证据与交接记录。

技能名称：`shidiao-research-copilot`  
当前版本：1.0

## 下载

**[查看完整 SKILL.md](skills/shidiao-research-copilot/SKILL.md)**

打开文件页面后，使用 **Raw / Download raw file** 保存原始 Markdown。也可以在仓库首页选择 **Code → Download ZIP** 下载全部文件。

只把文件当作工作指引使用时，下载 `SKILL.md` 即可。

## 可以做什么

| 模块 | 主要工作 |
| --- | --- |
| 选题与开题 | 收窄边界，判断渠道和实施可行性 |
| 文献与引用 | 核验来源、原文支持程度和研究缺口 |
| 调查设计 | 检查抽样、题项、访谈信息与研究问题的对应 |
| 预调查与实施 | 整理真实反馈、修订、复测和调查安排 |
| 数据整理 | 核对编码、缺失、异常、样本流转与版本 |
| 分析与复核 | 选择适切方法，检查分母、结果和解释边界 |
| 报告与答辩 | 让发现支持结论，让建议对应行动与验证 |
| 质量与提交 | 按影响排序修复问题，核对适用正式要求 |
| 按需增强 | 市场规模、用户细分、试点验证与金融主题检查 |

每次可以只处理一个具体问题，无需重新走完整流程。文件内包含团队项目状态块，以及文献证据、问题与测量、预调查修订、发现与行动、审查修复五张空模板。

## 使用方式

### 作为工作指引上传

将 `SKILL.md` 与本次项目材料一起上传给 AI，说明当前阶段和具体任务。搜索、统计和文件处理能力取决于所用工具。

### 安装为 Skill

按所用工具的安装方式导入 `skills/shidiao-research-copilot` 目录。保留：

- `SKILL.md`：完整工作指引及名称、描述。
- `agents/openai.yaml`：可选的界面名称与默认提示。

安装后通过技能名称调用，不同工具的调用方式以其实际支持为准。也可以向支持安装 GitHub 技能的助手提供本仓库链接，并指定目录 `skills/shidiao-research-copilot`。

## 三个调用示例

**选题与开题**

> 请使用 shidiao-research-copilot。我们准备研究【主题】，可接触【人群/渠道】，周期【时间】，已有【材料】。请判断边界与可行性，给出核心问题、资料获取路径和下一步交付。

**问卷与预调查审查**

> 请使用 shidiao-research-copilot，审查我们自行拟定的问卷和真实预调查记录。检查关键问题是否测量、受访者能否理解、跳转是否合理，以及哪些修改需要复测。请指出位置和依据。

**分析与报告复核**

> 请使用 shidiao-research-copilot，结合所附适用赛事AI条款，检查我们的真实分析输出和报告。核对样本、分母、解释边界、摘要数字和建议依据；区分已复算、仅解释输出和仍未核验的内容。

## 团队如何接力

维护同一份项目状态主版本，记录研究边界、已确认决定、资料版本、结果位置、负责人和未决问题。换成员或开新会话时，一起传递：

1. 本技能文件；
2. 最新项目状态；
3. 本次任务需要的材料。

技能不会自动同步各成员的聊天记录。问卷、总体、清理规则或分析版本改变后，检查图表、摘要、报告和PPT是否需要更新。

## 使用要求

使用真实调查资料，不将模拟回答、虚构访谈或未计算的结果写入研究结论。页数、匿名、评分、答辩时限及AI范围，按适用届次、组别、赛区和阶段的正式文件核对。

公开仓库用于保存技能和空模板；可识别的原始调查资料保存在团队受控位置。

## 方法来源

本文件结合公开方法思路，为市调团队独立重组流程。完整来源、具体文件和固定版本见 [SKILL.md 的来源与整合说明](skills/shidiao-research-copilot/SKILL.md)。

- [xiaoningwang/shidiao-skills](https://github.com/xiaoningwang/shidiao-skills)
- [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)
- [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)
- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills)
- [AAPOR 调查研究最佳实践](https://aapor.org/standards-and-ethics/best-practices/)

本仓库不打包上述项目的脚本或软件依赖，来源署名不表示原作者对本整合版的审核或背书。第三方材料的许可范围以各原项目为准。
