# 币安带单监控工具怎么选？5个工具的用途、费用与官方来源

原文链接 https://bn.9987620.xyz/compare

TRADER WATCH · 发布于 2026-11-19 · 更新于 2026-11-21

先分清你要研究谁的数据：带单员的公开记录、自己账户的成交，还是整个市场的行情。本页由TRADER WATCH维护者编写，包含本站及4个外部工具，不作收益排名；公开资料核对日期为2026年11月21日。

## 快速对比：5个工具解决什么问题

表格只记录已能从项目本身或官方文档核对的用途与接入条件。查看公开资料、分析个人账户与实际跟单是不同功能；具体费用、覆盖范围和可用条件以来源页面为准。

| 工具 | 主要观察对象 | 数据接入 | 用途与限制 | 费用口径 |
| --- | --- | --- | --- | --- |
| TRADER WATCH（本站） | 币安带单项目公开记录 | 无需个人币安API密钥 | 公开流水、K线买卖点、同轮连线和带时间的持仓推算；不下单 | 网页工具免费 |
| 币安官方带单页面与跟单 | 平台公开带单项目；跟单另需账户 | 按币安页面及账户规则 | 官方项目资料与跟单入口；公开范围由平台及交易员设置决定 | 实际跟单涉及交易费、利润分成等平台规则 |
| TradeVoyage | 自己的交易账户或已导入记录 | 可导入文件；自动导入需本人授权的读取API | 多交易所K线交易标记、仓位历史与统计；需自行部署 | 开源MIT；部署与第三方服务成本另计 |
| EdgeDepth | 市场订单流与历史行情 | 公开市场数据；托管访问按套餐 | 订单流与行情回放；不等同于指定带单员的成交记录 | 有免费层与付费套餐，额度见官方定价 |
| AlphaFox | 币安带单员、Hyperliquid地址及平台策略 | 公开页面与登录分析分开；实盘接入另需授权 | 带单员分析、历史仓位与流水；部分功能需Pro或以上 | 免费浏览与会员功能分开，见官方文档 |

## TRADER WATCH：按公开成交核对开平仓

本站将公开带单流水放回5分钟至日线六种周期K线，按数量归组并展示查询截止时间。它不读取用户私人账户，也不提供自动跟单。推算结论取决于基线、历史覆盖和数据延迟。

资料：[本站数据来源与推算规则](https://bn.9987620.xyz/methodology)

资料：[使用指南](https://bn.9987620.xyz/guide)

## 币安官方：项目资料与真实跟单入口

币安官方FAQ说明合约跟单会按所选带单组合自动复制交易。因此，免费浏览项目资料不能理解为跟单交易没有费用；利润分成、账户条件和执行规则应从官方说明核对。公开项目页也不能保证展示任意账户的全部隐藏仓位。

资料：[币安合约跟单FAQ（官方）](https://www.binance.com/en/support/faq/detail/6ed0995daf0b42d5816beaf1e31ca09d)

资料：[本文固定案例的公开带单项目](https://www.binance.com/zh-CN/copy-trading/lead-details/5075281354358777856)

## TradeVoyage：复盘自己导入的账户成交

项目名称为TradeVoyage。官方仓库列出了多交易所数据导入、K线交易标记、仓位历史与权益统计，提供文件导入及本人账户API导入方式。开源软件本身与运行环境、第三方服务的成本应分别计算。

资料：[TradeVoyage官方GitHub与README](https://github.com/0x0funky/TradeVoyage)

## EdgeDepth：回放市场，不是查询指定带单员

官方介绍侧重市场订单流和已记录行情回放。免费层与付费套餐的回放区间、市场覆盖和研究额度不同；使用前应核对所需日期是否有记录，以及当前套餐是否支持。

资料：[EdgeDepth官方FAQ](https://edgedepth.com/faq/)

资料：[EdgeDepth官方定价与额度](https://edgedepth.com/pricing)

## AlphaFox：公开带单员分析与账户执行分开

官方带单员分析文档支持币安带单项目ID或主页链接，以及Hyperliquid地址分析。币安报告、当前仓位等部分功能要求登录并达到Pro或以上；模拟盘与实盘执行是另外的流程，接入交易账户时的授权要求也不同。

资料：[AlphaFox带单员分析（官方）](https://www.alphafox.app/zh/docs/core-features/trader-dna)

资料：[AlphaFox账户与权限FAQ（官方）](https://www.alphafox.app/zh/docs/faq)

## 怎样自己核对，而不是只看比较表

先确认数据属于他人公开项目、本人账户还是市场。对齐同一时间区间的成交时间、合约方向、数量和均价；检查来源、分页覆盖与查询截止时间；最后保存导出记录和仍无法解释的缺口。数量能闭合只能证明所示记录的关系，不能证明账户没有其他隐藏仓位。

资料：[公开记录术语表](https://bn.9987620.xyz/glossary)

资料：[熬鹰BTC历史复盘与固定CSV](https://bn.9987620.xyz/articles/aoying-kline-review-btc-202610)

## 资料与记录

- [TRADER WATCH数据口径](https://bn.9987620.xyz/methodology)
- [币安合约跟单官方FAQ](https://www.binance.com/en/support/faq/detail/6ed0995daf0b42d5816beaf1e31ca09d)
- [TradeVoyage官方仓库](https://github.com/0x0funky/TradeVoyage)
- [EdgeDepth官方FAQ](https://edgedepth.com/faq/)
- [EdgeDepth官方定价](https://edgedepth.com/pricing)
- [AlphaFox带单员分析官方文档](https://www.alphafox.app/zh/docs/core-features/trader-dna)
- [AlphaFox官方FAQ](https://www.alphafox.app/zh/docs/faq)
