# efore-ai-video

Efore 第一期产品 AI 视频项目管理：产品资料、需求、脚本、分镜、提示词、工具评测、素材索引与成片交付。

当前范围仅为第一期：制作 IBUE48100、IBUE48200、ESmart-Li48160 的展会及展厅视频，暂不扩展到其他产品。

## 当前状态

截至 2026-11-05，已完成需求整理、官方工具资料初筛、6 条竞品与工业产品视频调研、执行流程草案及第一期成本估算与选型建议。预算口径仅含工具与素材等费用，暂不计人工成本；尚未进行付费样片测试，尚未冻结预算、成员分工或开工日期。

**第一期基准预算约 5,300 元，建议采购额度 6,000 元。** 下一步确认交付范围并开展约 800 元的同题样片测试，再校准正式预算；以上均为规划建议，尚未发生付费调用。

## 项目入口

| 内容 | 文件 |
| --- | --- |
| 组员原始文件及校验信息 | [原始资料](docs/source/README.md) |
| 关键需求与待确认差异 | [需求基线草案](projects/phase-01/01-requirements.md) |
| 阶段、责任、排期及交付 | [执行流程](projects/phase-01/02-workflow-and-schedule.md) |
| Kling、Seedance、Vidu、MiniMax、Runway 初筛 | [工具调研](research/ai-video-tools-2026-11-05.md) |
| 7 家厂商、11 个版本的评分、规格与成本（含可调权重及来源） | [模型对比 Excel](research/AI视频模型对比与评分_20261105.xlsx) · [Markdown 版](research/AI视频模型对比与评分_20261105.md) |
| 6 条官方视频、关键时间点、成色评价及第一期借鉴方案 | [竞品与工业产品视频调研](research/competitor-product-videos-2026-11-05.md) |
| 同题测试、评分与停止条件 | [样片测试方案](projects/phase-01/03-poc-plan.md) |
| 第一期成本明细、预算方法、情形测算和模型选择（暂不计人工） | [成本估算与模型选型](projects/phase-01/04-budget-method.md) |
| 逐镜头记录、费用、交付及变更模板 | [执行模板](templates/production-records.md) |
| 实际待办与依赖 | [GitHub Issues](https://github.com/ahhhhzzz/efore-ai-video/issues) |

## 使用方式

1. 项目负责人汇总需求，产品负责人核对结构、卖点和认证，需求方指定一位最终确认人。
2. 按阶段关闭 Issues；只有产出文件和确认记录齐全才算完成。方案草案不等于已审批，官网能力不等于产品实测效果。
3. 每条视频设 Video ID，每个独立镜头设 Shot ID。语言、字幕、编码派生版本复用 Shot ID，避免重复计算生成成本。
4. 文档和提示词存 GitHub；视频、CAD 和工程大文件存团队指定共享盘，在镜头台账中记录路径、版本及校验值。仓库内不放 API 密钥、临时签名下载链接。
5. 原始资料保留原貌，后续修订新增版本并记录差异；不把本次建议回写成组员已确认的结论。

## 第一期任务

| 任务 | 建议窗口 | 依赖 |
| --- | --- | --- |
| [#1 需求、资料与责任确认](https://github.com/ahhhhzzz/efore-ai-video/issues/1) | D1 | 需求及产品代表参与 |
| [#2 工具初筛及试验费用](https://github.com/ahhhhzzz/efore-ai-video/issues/2) | D2 | #1 |
| [#3 同题样片与费用实测](https://github.com/ahhhhzzz/efore-ai-video/issues/3) | D3–D4 | #1、#2 |
| [#4 分镜和正式预算](https://github.com/ahhhhzzz/efore-ai-video/issues/4) | D5–D6 | #1、#3 |
| [#5 素材与粗剪](https://github.com/ahhhhzzz/efore-ai-video/issues/5) | D7–D13 | #4 |
| [#6 评审、交付与复盘](https://github.com/ahhhhzzz/efore-ai-video/issues/6) | D14–D18 | #5 |

## 状态约定

待开始 → 进行中 → 待评审 → 已完成；依赖未满足时标记为阻塞。每项任务记录责任角色、负责人待定项、工作日窗口、前置任务和完成标准。

建议总排期为 18 个工作日，含 4 天前置研究与验证及 14 天制作交付。实际开始日期、展会截止日、团队人数与评审响应时间尚待确认；详见执行流程。
