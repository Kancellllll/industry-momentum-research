# 来源与阅读记录

核查日：2026年11月10日。实际动作：访问官方说明页及原论文出版商摘要；没有下载收益ZIP，没有阅读全文或复现论文。

## 数据说明

| 来源 | 本次核查到的内容 | 对本研究的影响 |
| --- | --- | --- |
| [French数据主页](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html) | 提供行业、因子和Mom下载入口；历史会重建；缺失值说明为-99.99或-999 | 原始批次归档、记录哈希，缺失值先处理再缩放 |
| [12行业构造](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/Data_Library/det_12_ind_port.html) | 六月底按SIC分类，随后七月至次年六月计算收益 | 需保存行业定义；不是12只上市ETF |
| [三因子说明](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/Data_Library/f-f_factors.html) | Mkt-RF为市场超额收益；RF来源自2024年6月起变化 | 市场总收益参考需加RF，记录RF来源变化 |
| [Mom说明](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/Data_Library/det_mom_factor.html) | 基于规模与过去2–12月个股收益形成的组合，赢家减输家 | 它是风险解释变量，不是本研究策略收益 |

主页还说明：自2025年1月数据发布起，研究收益由CRSP FIZ转为CIZ；月度股息再投资从月末约定改为除息日约定。历史当前版本也可能修订，不能按“2025年前FIZ、之后CIZ”自行拼接。实际下载后需核对各文件页眉及方法说明，本轮未进行跨版本定量比较。[官方来源](https://mba.tuck.dartmouth.edu/pages/faculty/ken.french/data_library.html)

本轮不把网页显示的最新终点当作实际文件覆盖范围，也不因已有2026年数据而扩大计划终点2025-12。

## 原始研究阅读卡

[Moskowitz与Grinblatt（1999），Do Industries Explain Momentum?](https://doi.org/10.1111/0022-1082.00146)，The Journal of Finance 54(4), 1249–1290。

已核查出版商书目信息与摘要：论文研究行业动量与个股动量的关系，并报告行业动量在其样本及控制变量下仍有解释力。这是原论文的发现，不是本项目已验证的结论。本项目采用12行业只做多设计，不能称为对原论文交易规则的精确复现。

第一周只做以下阅读：读标题和摘要，写下研究对象、作者想区分的问题，以及它与本项目的一个差异。全文的样本、行业分组、持有期和控制方法待后续阅读后记录，不能从摘要猜测。

| 待读问题 | 当前记录 |
| --- | --- |
| 原文样本与行业划分 | 待阅读全文核查 |
| 排序、持有期及多空规则 | 待阅读全文核查 |
| 对个股动量的控制如何实施 | 待阅读全文核查 |
| 本项目借鉴什么、改变什么 | 借鉴行业持续性问题；采用预设12行业、跳月、只做多和时间留出设计 |

[Bailey与López de Prado（2014），The Deflated Sharpe Ratio](https://www.davidhbailey.com/dhbpapers/deflated-sharpe.pdf)沿用原计划作为后续阅读，本轮未阅读或核查正文；目前不声称实现DSR。
