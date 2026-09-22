<div align="center">

[English](README.md) | [简体中文](README_ZH.md) | [日本語](README_JA.md)

<img src="images/logo.svg" width="120" height="120" alt="NuvexLens Logo">

# NuvexLens

**专业级智能金融图表与量化决策分析平台**

*整合高性能图表引擎、双盲回放训练、多因子量化信号、跨市场行情热力图、多维筛选器与深度投研知识库的一站式交易生态*

[![Platform](https://img.shields.io/badge/平台-Web-blue?style=flat-square)](https://nuvexlens.com)
[![Version](https://img.shields.io/badge/版本-v3.3-green?style=flat-square)](https://nuvexlens.com)
[![License](https://img.shields.io/badge/授权-Commercial-orange?style=flat-square)](https://nuvexlens.com)

[官方首页](https://nuvexlens.com) · [图表](https://chart.nuvexlens.com/) · [信号中心](https://chart.nuvexlens.com/signals/hub/strategy) · [行情](https://nuvexlens.com/quotes/) · [筛选器](https://nuvexlens.com/screener/) · [深度分析](https://chart.nuvexlens.com/signals/analysis) · [指标策略库](https://docs.nuvexlens.com/indicator-strategies/) · [文档中心](https://docs.nuvexlens.com)

</div>

---

## 声明与致谢

- **知识产权与商业授权**：**本项目为私有商业软件，非开源项目。** 未经授权，严禁复制、分发、逆向工程或商业转售。
- **技术基础与组件集成**：本项目图表模块基于 **TradingView** 开源图表库进行深度二次开发，并嵌入了 TradingView 官方发行的专业组件用于多维金融数据可视化与行情展示。
- **特别致谢**：在此衷心感谢 **[TradingView](https://www.tradingview.com/)** 团队为全球金融科技开发者提供如此卓越、专业、高性能的图表引擎底座与产品生态。

---

## 平台概览

NuvexLens 专为专业交易员、量化投资人与金融学习者打造。系统整合了多市场实时行情推流、多因子量化信号、宏观与板块热力图、多维条件选股、个股深度技术诊断以及完备的投研知识库，提供全流程交易分析与决策支持。

```
                    +---------------------------------------------+
                    |             NuvexLens 投研生态               |
                    +---------------------------------------------+
                                           |
     +-----------------+-------------------+-----------------+-----------------+
     |                 |                   |                 |                 |
[ 智能图表 ]      [ 信号中心 ]        [ 全球行情 ]      [ 多维筛选器 ]     [ 深度分析 ]
 chart.             signals/hub         quotes/           screener/         signals/analysis
 - 10屏多图联动     - 量化策略推荐      - 全球报价矩阵    - 多市场条件筛选   - 标的全景画像
 - 毫秒级K线推流    - 回测胜率追踪      - 行业板块热力图  - 基本面技术面组合 - 多周期技术共识
 - 双盲复盘训练     - 机构持仓追踪      - 情绪多空温度计  - 预设策略一键选   - 产业链壁垒评估
 - Pine脚本引擎     - 技术信号监控      - 链上合约数据    - 一键联动图表     - 关键位自动研判
     |                 |                   |                 |                 |
     +-----------------+-------------------+-----------------+-----------------+
                                           |
         +---------------------------------+---------------------------------+
         |                                 |                                 |
 [ 指标与策略精选库 ]              [ 知识库与文档中心 ]              [ 新闻雷达 TrendRadar ]
   docs.nuvexlens.com/               docs.nuvexlens.com                trendradar.nuvexlens.com
   indicator-strategies/             - 四语系统化教程                  - 7x24 全球财经快讯
   - 动态飙升与好评榜单              - 投研知识体系架构                - 多源异动舆情监测
   - 独家统计与实战指南              - 快速入门与快捷键
   - 社区开源合规收录
```

---

## 核心模块与直达链接

| 核心模块 | 核心定位 | 直达链接 | 核心能力与关键子页面 |
| :--- | :--- | :--- | :--- |
| **智能图表**<br>Smart Chart | 专业级多资产图表与双盲复盘训练系统 | [直达图表](https://chart.nuvexlens.com/) | 10屏多图联动、毫秒级数据流、100+内置与VIP指标、双盲复盘训练（Replay Trainer）、Pine Script 脚本引擎 |
| **信号中心**<br>Signals Hub | 量化策略推荐、技术信号监控与机构共识追踪 | [直达信号中心](https://chart.nuvexlens.com/signals/hub/strategy) | 策略综合推荐与回测追踪、[技术信号矩阵](https://chart.nuvexlens.com/signals/hub/technical)、[机构持仓与共识](https://chart.nuvexlens.com/signals/hub/holdings) |
| **全球行情**<br>Quotes | 全球资产报价矩阵、热力图与微观情绪仪表盘 | [直达行情](https://nuvexlens.com/quotes/) | 全球大盘指数列表、[行业板块热力图](https://nuvexlens.com/quotes/heatmap)、[市场微观情绪仪表盘](https://nuvexlens.com/quotes/sentiment)、[链上合约数据](https://nuvexlens.com/quotes/onchain-contracts) |
| **多市场筛选器**<br>Screener | 跨 A股/港股/美股/加密资产多维条件选股器 | [直达筛选器](https://nuvexlens.com/screener/) | 覆盖全市场标的、财务基本面与技术指标组合筛选、预设经典策略一键选股、结果一键联动图表与分析 |
| **深度分析**<br>Analysis | 标的代码直达一站式全景投研与技术共识评分 | [直达深度分析](https://chart.nuvexlens.com/signals/analysis) | 多时间框架综合技术评级、量化诊断打分、关键阻力支撑自动测算、Serenity 产业链瓶颈评分 |
| **精选指标与策略库**<br>Indicator & Strategy | 社区开源与独家量化指标库、动态排行榜与实战指南 | [直达指标策略库](https://docs.nuvexlens.com/indicator-strategies/) | 多维热度与飙升榜单、独家多周期实战统计、分类逻辑索引、Pine源码Diff对比、[自研增强指标](https://docs.nuvexlens.com/indicator-strategies/closed-source/)、[脚本使用教学](https://docs.nuvexlens.com/indicator-strategies/script-usage/) |
| **文档与知识库**<br>Help Center | 多语言交易教程、知识库与系统指南 | [直达文档中心](https://docs.nuvexlens.com)<br>[直达帮助中心](https://help.nuvexlens.com) | 中/繁/英/日四语支持、系统化量化与交易工作流、快速开始与 FAQ |
| **新闻雷达**<br>TrendRadar | 7x24 全球财经要闻、多源舆情与异动公告雷达 | [直达新闻雷达](https://trendradar.nuvexlens.com/) | 实时财经快讯聚合、智能异动提炼、多源情绪与宏观日历 |

---

## 模块详细介绍

### 1. 智能图表 (Smart Chart)
- **直达链接**：[https://chart.nuvexlens.com/](https://chart.nuvexlens.com/)
- **核心功能**：
  - **毫秒级流式数据推流**：基于高可用 WebSocket 与网关架构，实现极低延迟的价格变动与分时明细推送。
  - **多屏分屏与多周期联动**：支持单屏 1 至 10 个图表灵活排列，不同周期、不同标的保持十字光标、时间轴与图形工具无缝同步。
  - **沉浸式双盲复盘训练系统 (Replay Trainer)**：
    - 支持从历史任意时间点开启高精度复盘模拟。
    - 独创双盲训练模式：支持隐藏代码与历史日期，排除后视偏差，纯粹依靠形态、量价与技术指标锤炼真实交易直觉。
    - 支持 0.5x 至 10x 自由调速与单步 K 线推进。
  - **100+ 专业技术指标与独家 VIP 指标**：包含智能多空波段、筹码分布、主力资金流向、分型买卖点提示等。
  - **Pine Script 脚本转译与运行引擎**：兼容社区主流 Pine 脚本语法，支持用户指标导入、参数实时调整与独立沙箱运行。

### 2. 信号中心 (Signals Hub)
- **直达链接**：[https://chart.nuvexlens.com/signals/hub/strategy](https://chart.nuvexlens.com/signals/hub/strategy)
- **核心子页面**：
  - **综合量化策略**：[https://chart.nuvexlens.com/signals/hub/strategy](https://chart.nuvexlens.com/signals/hub/strategy)
  - **技术信号监控**：[https://chart.nuvexlens.com/signals/hub/technical](https://chart.nuvexlens.com/signals/hub/technical)
  - **机构持仓共识**：[https://chart.nuvexlens.com/signals/hub/holdings](https://chart.nuvexlens.com/signals/hub/holdings)
- **核心功能**：
  - **策略综合推荐与信号捕捉**：聚合多因子规则模型，盘中与盘后实时输出高质量交易信号与置信度。
  - **回测追踪与透明度验证**：全面展示各策略历史胜率、盈亏比、最大回撤与累计收益走势，告别虚假承诺。
  - **多维度技术信号矩阵**：实时扫描金叉死叉、布林带挤压突破、RSI 超买超卖背离等异动信号。
  - **机构持仓共识 (Holdings Tracker)**：深度整合 SEC 13F 顶级对冲基金季度持仓、ARK 每日交易明细、美国国会交易员持仓等，计算聪明资金（Smart Money）共识重合度与持仓变动方向。

### 3. 全球行情中心 (Quotes)
- **直达链接**：[https://nuvexlens.com/quotes/](https://nuvexlens.com/quotes/)
- **核心子页面**：
  - **板块与行业热力图**：[https://nuvexlens.com/quotes/heatmap](https://nuvexlens.com/quotes/heatmap)
  - **市场情绪仪表盘**：[https://nuvexlens.com/quotes/sentiment](https://nuvexlens.com/quotes/sentiment)
  - **链上合约数据**：[https://nuvexlens.com/quotes/onchain-contracts](https://nuvexlens.com/quotes/onchain-contracts)
- **核心功能**：
  - **全球报价总览**：A股主要指数、港股恒生指数系列、美股标普/纳指/道指及主流加密资产报价矩阵。
  - **板块树状热力图 (Treemap Heatmap)**：
    - TradingView 交互风格，支持按市值面积、涨跌幅度、成交额动态呈现。
    - 支持多层级钻取（大类行业 -> 细分板块 -> 龙头个股）与流畅双向缩放。
  - **市场微观情绪仪表盘 (Sentiment Dashboard)**：
    - 整合加密货币多空人数比、资金费率热力。
    - 外汇多空偏好、社交网络情绪指数与技术面多空综合打分。
  - **衍生品微观结构**：未平仓合约量 (Open Interest)、爆仓分布与多空清算图谱。

### 4. 多市场筛选器 (Screener)
- **直达链接**：[https://nuvexlens.com/screener/](https://nuvexlens.com/screener/)
- **核心功能**：
  - **跨市场覆盖**：全面支持中国 A 股（沪深北）、美股（纽交所/纳斯达克/美交所）、港股及数字加密资产。
  - **百项指标交叉过滤**：
    - 基本面指标：市盈率 (PE)、市净率 (PB)、净资产收益率 (ROE)、股息率、营收/净利复合增长率等。
    - 技术面指标：均线多头排列、均线距离、成交量激增倍数、ATR 波动率、突破前高/前低等。
  - **预设经典推荐策略**：内置“低估值高股息”、“强势放量突破”、“白马稳健增长”、“短线动量反弹”等经过量化验证的策略预设，一键选股。
  - **无缝生态联动**：筛选结果点击即可联动到图表页面快速复核技术形态，或跳转深度分析页面查看综合诊断。

### 5. 深度分析 (Stock Analysis & Research)
- **直达链接**：[https://chart.nuvexlens.com/signals/analysis](https://chart.nuvexlens.com/signals/analysis)
- **核心功能**：
  - **代码直达全景研报**：在搜索栏或 URL 中输入任意标的代码，秒级生成涵盖技术面、资金面与行业基本面的全景诊断。
  - **多时间框架技术共识评级**：从 15分钟、1小时到日线、周线等多周期，综合移动平均线与震荡指标计算买卖建议评级。
  - **智能关键点位研判**：基于成交量分布 (Volume Profile) 与斐波那契模型，自动标识核心支撑位、阻力位与波动区间。
  - **Serenity 产业链与瓶颈评分**：深入剖析上下游供应链关系、产业卡脖子环节定位与核心技术护城河评分。

### 6. 精选指标与策略库 (Indicator & Strategy Library)
- **直达链接**：[https://docs.nuvexlens.com/indicator-strategies/](https://docs.nuvexlens.com/indicator-strategies/)
- **核心子模块与入口**：
  - **指标库总览与分类索引**：[https://docs.nuvexlens.com/indicator-strategies/](https://docs.nuvexlens.com/indicator-strategies/)
  - **动态热度与飙升榜单**：[https://docs.nuvexlens.com/indicator-strategies/rankings/trending/](https://docs.nuvexlens.com/indicator-strategies/rankings/trending/)
  - **自研与独家增强指标 (闭源精选)**：[https://docs.nuvexlens.com/indicator-strategies/closed-source/](https://docs.nuvexlens.com/indicator-strategies/closed-source/)
  - **脚本使用与参数配置指南**：[https://docs.nuvexlens.com/indicator-strategies/script-usage/](https://docs.nuvexlens.com/indicator-strategies/script-usage/)
- **核心特色与独家统计**：
  - **独家热度与趋势动态统计**：持续跟踪量化指标在全网社区的使用热度与增长斜率，提供涵盖“飙升榜 (Trending)”、“顶尖好评 (Top Rated)”与“编辑精选 (Editor's Picks)”的多维动态榜单，结合独家活跃度算法过滤失效低质脚本，帮交易员第一时间捕获高价值量化逻辑。
  - **指标实战运用的深度解析**：打破单一的代码堆砌，每款指标均配备由浅入深的**实战技法拆解**——包括不同行情（单边趋势/震荡整理）下的参数自适应建议、多时间周期共振验证机制、虚假突破过滤规则以及仓位止盈止损配合指南。
  - **全景逻辑分类与多维检索**：系统化归类为趋势跟踪 (Trend)、动量摆荡 (Momentum)、成交量分布 (Volume Profile)、波动率范围 (Volatility) 与智能资金市场结构 (SMC / 缠论自动画线) 等核心领域，支持按交易流派精准定位。
  - **版本演进轨迹与源码 Diff 对比**：支持在线查看指标历史版本演进与代码变更对比 (Diff)，清晰洞察算法改良脉络；支持 Pine 脚本源码一键复制与快速导入图表引擎。
  - **自研高阶增强与经典指标融合**：除社区经典算法外，平台自主研发了多款闭源增强指标，针对国内与国际市场特征深度重构，提供更敏锐的主力异动捕获与买卖点指引。
- **版权合规与致谢声明**：
  - **来源与合规说明**：本模块收录的开源指标与策略脚本均源自 **TradingView 开源社区**，严格遵循 TradingView 社区发行规范（House Rules）以及原作者所声明的开源许可协议（包括 MPL 2.0、Apache 2.0、MIT、GPL 等）进行多语言本土化翻译、算法原理整理与交互式呈现。
  - **尊重原创知识产权**：每个指标详情页均清晰标明原作者姓名/社区主页、TradingView 官方原始发布链接、原始版本号及对应开源协议，完整保留原作者署名权。
  - **致谢作者与平台**：在此向无私奉献开源智慧成果的广大社区 Pine 脚本作者、量化开拓者致以崇高的敬意，并由衷致谢 **[TradingView](https://www.tradingview.com/)** 平台为全球金融分析与程序化交易搭建的开放、协作、繁荣的创新社区生态。

### 7. 文档中心与知识库 (Help Center & Docs)
- **直达链接**：
  - 文档中心：[https://docs.nuvexlens.com](https://docs.nuvexlens.com)
  - 帮助中心：[https://help.nuvexlens.com](https://help.nuvexlens.com)
- **核心功能**：
  - **多语言全覆盖**：支持简体中文、繁体中文、English、日本語，提供无障碍国际化学习体验。
  - **系统化交易进阶教程**：从新手入门配置、数据源原理解析，到高阶指标编写、量化策略构建与复盘心法。
  - **知识体系与操作手册**：覆盖账号体系、多端设备云同步、快捷键操作手册与常见问题实时解答。

### 8. 新闻雷达 (TrendRadar)
- **直达链接**：[https://trendradar.nuvexlens.com/](https://trendradar.nuvexlens.com/)
- **核心功能**：
  - **7x24 小时全球财经要闻聚合**：直连全球主流财经资讯与行业信源，毫秒级推送快讯。
  - **热点题材与异动舆情追踪**：AI 驱动的新闻语义识别与主题聚类，自动关联涉及的股票与行业板块。
  - **重大事件日历**：重要央行决议、宏观经济数据发布、财报公布节点清晰呈现。

---

## 支持市场与覆盖资产

| 市场类别 | 覆盖范围 | 数据类型 | 更新机制 |
| :--- | :--- | :--- | :--- |
| **中国 A 股** | 上交所、深交所、北交所全标的 | 实时行情、Tick 明细、完整历史日/分K线、除权除息数据 | WebSocket 毫秒级推流 + 专线数据网关 |
| **美股** | 纳斯达克 (NASDAQ)、纽交所 (NYSE)、美交所 (AMEX) | 盘前、盘中、盘后全时段实时流与多周期历史数据 | 国际化流媒体专线 |
| **港股** | 香港联合交易所 (HKEX) 全部正股与 ETF | 实时逐笔、十档盘口与历史行情 | 港股专用行情网关 |
| **加密货币** | 全球主流交易对（BTC、ETH、SOL 等现货与永续合约） | 毫秒级实时价格、深度图、资金费率与链上持仓 | 直连主流交易所 WebSocket 数据流 |
| **期货与大宗商品** | 国内外主要商品期货、股指期货主力连续合约 | 实时报价与连续历史数据 | 专线行情适配器 |

---

## 推荐分析工作流

1. **宏观与市场扫描**：
   - 打开 [行情中心](https://nuvexlens.com/quotes/) 查看全球指数走向。
   - 通过 [行业热力图](https://nuvexlens.com/quotes/heatmap) 定位今日资金聚集的热点行业与领涨板块。
2. **多维筛选与初选池构建**：
   - 打开 [多市场筛选器](https://nuvexlens.com/screener/)，应用预设策略或自定义组合指标（如突破年线 + 换手率大于 3%）。
   - 将符合条件的标的加入云端自选列表。
3. **信号核对与策略验证**：
   - 进入 [信号中心](https://chart.nuvexlens.com/signals/hub/strategy) 检查目标标的是否命中近期高置信度量化推荐策略，并参考历史胜率表现。
   - 查看 [机构持仓共识](https://chart.nuvexlens.com/signals/hub/holdings)，确认顶级机构或聪明资金的持仓态度。
4. **图表深度研判与指标调用**：
   - 点击标的直达 [智能图表](https://chart.nuvexlens.com/)，启用多周期多图联动观察中长线趋势与分时买卖点。
   - 结合 [指标策略精选库](https://docs.nuvexlens.com/indicator-strategies/) 中的前沿量化策略与 Pine 脚本实战解析，叠加筹码分布与独家增强指标，精准测算入场点与盈亏比。
5. **深度基本面与产业链核对**：
   - 在 [深度分析](https://chart.nuvexlens.com/signals/analysis) 中查阅全景画像与供应链瓶颈评分。
6. **历史复盘与直觉打磨**：
   - 利用图表的 [双盲复盘训练系统](https://chart.nuvexlens.com/)，对同类形态历史行情进行盲测模拟推演，持续提升实战胜率。

---

## 常见问题 (FAQ)

<details>
<summary><b>NuvexLens 是否需要安装桌面客户端？</b></summary>
<br>
无需安装任何客户端。NuvexLens 采用纯 Web 标准架构开发，优化支持现代主流桌面与移动端浏览器（Chrome、Edge、Safari、Firefox 等），打开网页即可享受媲美桌面原生客户端的流畅体验。
</details>

<details>
<summary><b>数据推流的更新延迟是多少？</b></summary>
<br>
行情数据与技术信号均通过分布式 WebSocket 专线推流，延迟控制在毫秒级别。盘后历史数据与财务基本面数据每日收盘后自动校准入库。
</details>

<details>
<summary><b>自选股和图表分析设置是否支持跨设备同步？</b></summary>
<br>
完全支持。用户在登录状态下的自选列表、图表画线、指标模板、筛选器自定义预设等，均自动实时加密同步至云端。
</details>

<details>
<summary><b>双盲复盘训练与常规历史行情查看有何不同？</b></summary>
<br>
常规查看历史行情容易陷入“事后诸葛亮”的后视偏差。NuvexLens 独创的双盲模式隐藏了具体股票代码与历史日期区间，让交易者在完全未知的走势推进中检验技术分析系统的有效性，真正建立可靠的交易纪律。
</details>

---

## 联系与技术支持

- 官方网站：[nuvexlens.com](https://nuvexlens.com)
- 知识库与文档：[docs.nuvexlens.com](https://docs.nuvexlens.com)
- 商务合作与技术支持：support@nuvexlens.com

---

<div align="center">

**NuvexLens** — 专为交易员与学习者打造的智能金融分析平台

Empowering Professional Trading Decisions

Copyright © 2024-2026 NuvexLens. All Rights Reserved.

</div>
