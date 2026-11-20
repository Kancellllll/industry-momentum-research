# Industry Momentum Across Market Regimes

**行业动量信号的样本外有效性与失效机制研究**
Out of Sample Validation and Failure Analysis

A learning and research project using Kenneth French academic portfolios. Current stage: protocol draft and foundational learning. No research data, backtests or empirical performance claims. The final historical holdout remains closed.

## 当前状态（2026年11月20日）

研究过去表现较强的行业能否继续相对较强，以及成本、因子暴露、市场状态和极端时期如何影响结果。没有稳定优势也是应当保留的结果。

| 项目 | 实际状态 |
| --- | --- |
| 研究计划、协议、数据字典 | 已有首稿；协议未冻结 |
| 基础学习 | 已开始；保留一个正确作答及待理解问题 |
| 数据下载与质量检查 | 未开展 |
| 研究代码、回测和因子分析 | 未开展 |
| 2015至2025年最终历史留出期 | 未评估；须先冻结规则 |

十二周是计划，不是已完成经历。教学虚构数字不构成实证结果。

## 阅读与复核入口

- [研究协议](docs/RESEARCH_PROTOCOL.md)：假设、排序窗口、成本口径、时间切分及冻结条件。
- [学习记录](docs/LEARNING_LOG.md)：本人回答、AI解释和仍需验证的理解分别记录。
- [复核说明](docs/REVIEW_GUIDE.md)：目前可以检查什么、以后怎样检验成果。
- [数据字典](docs/DATA_DICTIONARY.md)与[来源笔记](docs/SOURCES.md)：字段、版本和证据范围。
- [实验登记](experiments/REGISTER.md)：保留全部尝试，目前尚无实验。
- [进展记录](docs/PROGRESS.md)、[十二周计划](PROJECT_PLAN.md)及[第一周练习](docs/WEEK_01.md)。

## 拟定设计

French 12行业月度组合；按持有月t以前的t-12至t-2复合收益排序，跳过t-1，等权持有前三行业。开发期1963至2002年，验证期2003至2014年，2015至2025年在协议冻结前禁止绩效评估。具体以最终冻结协议为准。

French组合是学术研究组合，不能当作可直接交易ETF的实盘表现。历史当前版本可能修订；成本是研究假设，美国行业结论不直接推广至其他市场。

## 目录与复现状态

| 目录 | 用途 |
| --- | --- |
| docs/ | 协议、学习、口径与复核说明 |
| data/raw/ 与 data/processed/ | 数据归档及标准化说明；数据本身不提交 |
| experiments/ | 全部实验登记 |
| reports/ | 报告模板，尚无结果报告 |
| .github/ | 复核Issue模板 |

当前只需阅读Markdown和手算，没有依赖安装步骤、策略执行入口或可复现的实证结果。后续代码随实际学习逐步加入，并记录数据批次、环境与运行命令。

欢迎通过仓库Issues指出计算、时间顺序、数据口径或证据不足的问题，参见[参与复核](CONTRIBUTING.md)。

AI协助披露：Codex协助整理文档和概念解释；本人回答单独标识，不将AI内容写成已独立掌握的技能。
