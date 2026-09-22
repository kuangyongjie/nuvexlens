<div align="center">

[English](README.md) | [简体中文](README_ZH.md) | [日本語](README_JA.md)

<img src="images/logo.svg" width="120" height="120" alt="NuvexLens Logo">

# NuvexLens

**Professional Smart Financial Charting & Quantitative Decision Platform**

*A unified trading ecosystem combining a high-performance charting engine, blind replay training, multi-factor quantitative signals, cross-market heatmaps, multi-dimensional stock screening, and an institutional research knowledge base.*

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://nuvexlens.com)
[![Version](https://img.shields.io/badge/Version-v3.3-green?style=flat-square)](https://nuvexlens.com)
[![License](https://img.shields.io/badge/License-Commercial-orange?style=flat-square)](https://nuvexlens.com)

[Website](https://nuvexlens.com) · [Chart](https://chart.nuvexlens.com/) · [Signals Hub](https://chart.nuvexlens.com/signals/hub/strategy) · [Quotes](https://nuvexlens.com/quotes/) · [Screener](https://nuvexlens.com/screener/) · [Analysis](https://chart.nuvexlens.com/signals/analysis) · [Indicators & Strategies](https://docs.nuvexlens.com/indicator-strategies/) · [Docs](https://docs.nuvexlens.com)

</div>

---

## Disclaimer & Acknowledgements

- **Proprietary Commercial Software**: **This is a proprietary commercial software and NOT an open-source project.** Unauthorized copying, distribution, decompilation, or commercial resale is strictly prohibited.
- **Charting Engine & Components**: The charting engine of this project is custom-developed based on the **TradingView** Charting Library, with embedded official TradingView components for professional financial data visualization.
- **Acknowledgements**: We extend our sincere gratitude to the **[TradingView](https://www.tradingview.com/)** team for providing the global fintech developer community with such an exceptional, high-performance charting foundation and product ecosystem.

---

## Ecosystem Overview

NuvexLens is purpose-built for active traders, quantitative researchers, and financial learners. The platform converges millisecond-grade real-time market data streaming, algorithmic strategy recommendations, macro and sector heatmaps, flexible multi-dimensional screening, in-depth technical diagnostics, and a comprehensive educational knowledge base into an integrated, frictionless workflow.

```
                    +---------------------------------------------+
                    |             NuvexLens Ecosystem             |
                    +---------------------------------------------+
                                           |
     +-----------------+-------------------+-----------------+-----------------+
     |                 |                   |                 |                 |
[ Smart Chart ]   [ Signals Hub ]      [ Market Quotes ]   [ Screener ]      [ Analysis ]
 chart.             signals/hub         quotes/             screener/         signals/analysis
 - 10-chart sync    - Quant strategies  - Global matrices   - Cross-market    - Panoramic dossier
 - Low-latency tick - Backtest tracking - Treemap heatmaps  - Metric filters  - Multi-timeframe
 - Blind replay     - Holdings tracker  - Sentiment meters  - Preset formulas - Bottleneck score
 - Pine execution   - Technical alerts  - On-chain data     - Seamless chart  - Auto S/R levels
     |                 |                   |                 |                 |
     +-----------------+-------------------+-----------------+-----------------+
                                           |
         +---------------------------------+---------------------------------+
         |                                 |                                 |
 [ Indicator Library ]             [ Docs & Help Center ]            [ TrendRadar News ]
   docs.nuvexlens.com/               docs.nuvexlens.com                trendradar.nuvexlens.com
   indicator-strategies/             - 4-language guides               - 24/7 financial alerts
   - Trending & top-rated boards     - Knowledge base curriculum       - Multi-source sentiment
   - Proprietary metrics & guides    - Shortcuts & fast setup
   - Open-source compliance
```

---

## Core Modules & Direct Access Links

| Module | Core Purpose | Direct Link | Key Capabilities & Deep Links |
| :--- | :--- | :--- | :--- |
| **Smart Chart** | Professional multi-asset charting and blind replay simulator | [Open Chart](https://chart.nuvexlens.com/) | Up to 10 synchronized viewports, millisecond data feeds, 100+ native & VIP indicators, Replay Trainer, and Pine Script runtime |
| **Signals Hub** | Quantitative strategies, technical monitors, and institutional consensus | [Open Signals Hub](https://chart.nuvexlens.com/signals/hub/strategy) | Algorithmic recommendations, transparent win-rate tracking, [Technical Signals](https://chart.nuvexlens.com/signals/hub/technical), and [Holdings Tracker](https://chart.nuvexlens.com/signals/hub/holdings) |
| **Market Quotes** | Global market matrices, sector heatmaps, and sentiment dashboards | [Open Quotes](https://nuvexlens.com/quotes/) | Global indices overview, [Sector Treemap Heatmap](https://nuvexlens.com/quotes/heatmap), [Market Sentiment Dashboard](https://nuvexlens.com/quotes/sentiment), and [On-Chain Contracts](https://nuvexlens.com/quotes/onchain-contracts) |
| **Multi-Market Screener** | Cross-market quantitative screening for CN, HK, US, and Crypto | [Open Screener](https://nuvexlens.com/screener/) | Full universe coverage, hundreds of fundamental & technical criteria, verified preset strategies, and direct one-click chart linkage |
| **Stock Analysis** | Panoramic asset dossier, technical consensus, and supply-chain research | [Open Analysis](https://chart.nuvexlens.com/signals/analysis) | Instant ticker lookup, multi-timeframe technical ratings, automated support/resistance zones, and Serenity bottleneck scorecards |
| **Indicator & Strategy Library** | Curated open-source & proprietary indicators, dynamic leaderboards, and execution guides | [Open Library](https://docs.nuvexlens.com/indicator-strategies/) | Dynamic trending & top-rated rankings, multi-timeframe execution metrics, Pine source diff viewer, [Proprietary Indicators](https://docs.nuvexlens.com/indicator-strategies/closed-source/), and [Script Usage Guide](https://docs.nuvexlens.com/indicator-strategies/script-usage/) |
| **Help Center & Docs** | Multi-lingual trading tutorials, knowledge base, and platform manuals | [Open Docs](https://docs.nuvexlens.com)<br>[Open Help Center](https://help.nuvexlens.com) | Full support for EN / ZH-CN / ZH-TW / JA, systematic workflows, tutorials, and comprehensive FAQ |
| **TrendRadar News** | 24/7 global financial news wire, event calendar, and sentiment radar | [Open TrendRadar](https://trendradar.nuvexlens.com/) | Real-time news aggregation, AI entity tagging, market-moving headlines, and macroeconomic releases |

---

## Detailed Module Breakdown

### 1. Smart Chart
- **Direct Link**: [https://chart.nuvexlens.com/](https://chart.nuvexlens.com/)
- **Core Features**:
  - **Ultra Low-Latency Streaming**: Powered by distributed WebSocket bridges and dedicated gateways for instant quote updates and sub-second order book refreshes.
  - **Multi-Chart Grid & Cross-Timeframe Sync**: Arrange up to 10 viewports on a single display with coordinated crosshairs, timeline panning, and drawing sync.
  - **Immersive Replay Trainer (Blind Mode)**:
    - Launch historical market replay from any point in time with tick-accurate fidelity.
    - Specialized Blind Mode masks instrument tickers and dates, eliminating hindsight bias and forcing disciplined reliance on pure price action and technical structure.
    - Adjustable playback speeds from 0.5x to 10x with manual step-by-step bar advance.
  - **100+ Indicators & Exclusive VIP Studies**: Includes adaptive multi-timeframe trend ribbons, volume profiles, institutional capital flow trackers, and fractal buy/sell alerts.
  - **Pine Script Compiler & Execution Runtime**: Parse and execute community Pine Script indicators safely inside an isolated browser sandbox.

### 2. Signals Hub
- **Direct Link**: [https://chart.nuvexlens.com/signals/hub/strategy](https://chart.nuvexlens.com/signals/hub/strategy)
- **Sub-pages**:
  - **Quant Strategies**: [https://chart.nuvexlens.com/signals/hub/strategy](https://chart.nuvexlens.com/signals/hub/strategy)
  - **Technical Signals**: [https://chart.nuvexlens.com/signals/hub/technical](https://chart.nuvexlens.com/signals/hub/technical)
  - **Holdings Tracker**: [https://chart.nuvexlens.com/signals/hub/holdings](https://chart.nuvexlens.com/signals/hub/holdings)
- **Core Features**:
  - **Algorithmic Signal Generation**: Combines multi-factor models and statistical rules to discover high-probability long/short opportunities.
  - **Auditable Backtest & Win-Rate Tracking**: Completely transparent historical statistics, win rates, profit factors, max drawdowns, and performance equity curves.
  - **Real-Time Technical Monitor**: Continuous scanning for moving average crossovers, Bollinger Band squeeze breakouts, RSI divergences, and candlestick reversals.
  - **Institutional Holdings & Consensus Tracker**: Aggregates SEC 13F filings from elite hedge funds, daily ARK ETF trades, and US Congressional disclosures to identify institutional conviction and positioning shifts.

### 3. Market Quotes & Heatmaps
- **Direct Link**: [https://nuvexlens.com/quotes/](https://nuvexlens.com/quotes/)
- **Sub-pages**:
  - **Sector Heatmap**: [https://nuvexlens.com/quotes/heatmap](https://nuvexlens.com/quotes/heatmap)
  - **Market Sentiment**: [https://nuvexlens.com/quotes/sentiment](https://nuvexlens.com/quotes/sentiment)
  - **On-Chain Contracts**: [https://nuvexlens.com/quotes/onchain-contracts](https://nuvexlens.com/quotes/onchain-contracts)
- **Core Features**:
  - **Global Benchmark Matrices**: Real-time quotes for major indices across US (S&P 500, Nasdaq, Dow Jones), China A-Shares, Hong Kong Hang Seng, and benchmark cryptos.
  - **Dynamic Treemap Heatmap**:
    - TradingView-inspired hierarchical treemap visualized by market cap weighting, percentage change, or turnover volume.
    - Multi-level drill-down capabilities (Macro Sector -> Sub-Industry -> Individual Leader) with fluid bidirectional zooming.
  - **Microstructure Sentiment Dashboard**:
    - Crypto Long/Short positioning ratio and funding rate heatmaps.
    - Forex retail sentiment gauge, social volume indices, and consensus technical ratings.
  - **Derivatives Liquidity**: Open interest metrics, liquidation heatmaps, and options gamma exposure indicators.

### 4. Multi-Market Screener
- **Direct Link**: [https://nuvexlens.com/screener/](https://nuvexlens.com/screener/)
- **Core Features**:
  - **Comprehensive Coverage**: Evaluates equities across Shanghai, Shenzhen, Beijing, NYSE, NASDAQ, AMEX, HKEX, and leading digital assets.
  - **Extensive Filtering Dimensions**:
    - Fundamental Metrics: P/E, P/B, ROE, Dividend Yield, Revenue & EPS Compound Growth Rates, Free Cash Flow.
    - Technical Filters: Moving average alignment, price distance from moving averages, volume surge multiples, ATR volatility, 52-week breakout levels.
  - **Curated Strategy Presets**: Out-of-the-box quantitative presets including "High Dividend & Low Valuation", "Volume Surge Breakout", "Steady Blue-Chip Compounders", and "Short-term Momentum Swing".
  - **Ecosystem Integration**: Instantly view filtered securities on the chart or transition to the deep analysis dossier with a single click.

### 5. In-Depth Stock Analysis
- **Direct Link**: [https://chart.nuvexlens.com/signals/analysis](https://chart.nuvexlens.com/signals/analysis)
- **Core Features**:
  - **Direct Ticker Lookup**: Enter any supported stock or crypto ticker in the search bar or URL query to immediately generate a comprehensive diagnostic report.
  - **Multi-Timeframe Technical Consensus**: Aggregates oscillators and moving averages across 15m, 1h, 4h, Daily, and Weekly horizons into actionable Buy/Sell/Neutral consensus ratings.
  - **Automated Structure & Support/Resistance Detection**: Identifies critical institutional liquidity pools, volume profiles, and key Fibonacci reaction zones.
  - **Serenity Supply-Chain & Bottleneck Analysis**: Evaluates upstream/downstream dependencies, market share concentration, critical technological choke-points, and competitive moat strength.

### 6. Indicator & Strategy Library
- **Direct Link**: [https://docs.nuvexlens.com/indicator-strategies/](https://docs.nuvexlens.com/indicator-strategies/)
- **Core Sub-Modules & Deep Links**:
  - **Curated Library Overview & Index**: [https://docs.nuvexlens.com/indicator-strategies/](https://docs.nuvexlens.com/indicator-strategies/)
  - **Dynamic Trending & Top-Rated Boards**: [https://docs.nuvexlens.com/indicator-strategies/rankings/trending/](https://docs.nuvexlens.com/indicator-strategies/rankings/trending/)
  - **Proprietary & Enhanced Indicators (Closed Source)**: [https://docs.nuvexlens.com/indicator-strategies/closed-source/](https://docs.nuvexlens.com/indicator-strategies/closed-source/)
  - **Script Usage & Parameter Setup Guide**: [https://docs.nuvexlens.com/indicator-strategies/script-usage/](https://docs.nuvexlens.com/indicator-strategies/script-usage/)
- **Key Capabilities & Proprietary Edge**:
  - **Proprietary Popularity & Momentum Metrics**: Monitors real-time community adoption velocity and activity scores, ranking scripts across "Trending", "Top Rated", and "Editor's Picks" while automatically filtering deprecated or redundant algorithms to surface actionable alpha.
  - **In-Depth Execution & Application Playbooks**: Goes beyond static source code by providing exhaustive tactical guides—including adaptive parameter tuning across trending vs. ranging markets, multi-timeframe confirmation frameworks, false breakout filters, and stop-loss/take-profit risk models.
  - **Comprehensive Categorization & Fast Discovery**: Structured into Trend Following, Momentum & Oscillators, Volume & Order Flow Profiles, Volatility Ranges, and Smart Money / Market Structure (SMC / Automated Chanlun Bi-Duan Centers).
  - **Evolution Tracking & Source Code Diff Viewer**: Enables side-by-side historical version diff comparisons to inspect algorithmic optimizations; provides one-click Pine Script copying and chart injection.
  - **Proprietary Alpha Enhancements**: Complements open-source classics with in-house proprietary algorithms tailored for domestic and global microstructures, offering enhanced institutional flow tracking and high-probability trigger signals.
- **Copyright Compliance & Acknowledgements**:
  - **Origin & Licensing**: All open-source indicator and strategy scripts in this library originate from the **TradingView Open-Source Community**, curated, translated, and presented in strict compliance with TradingView House Rules and respective author open-source licenses (MPL 2.0, Apache 2.0, MIT, GPL, etc.).
  - **Respect for Intellectual Property**: Every script page prominently attributes the original author, links to the official TradingView publication, and retains original license identifiers and copyright notices.
  - **Sincere Gratitude**: We express our deepest gratitude to the global Pine Script creator community for their open-source contributions, and to the **[TradingView](https://www.tradingview.com/)** platform for fostering the world's most vibrant and innovative financial charting ecosystem.

### 7. Help Center & Knowledge Base
- **Direct Link**:
  - Documentation: [https://docs.nuvexlens.com](https://docs.nuvexlens.com)
  - Help Center: [https://help.nuvexlens.com](https://help.nuvexlens.com)
- **Core Features**:
  - **4-Language Support**: Fully localized in English, Simplified Chinese, Traditional Chinese, and Japanese.
  - **Structured Trading Curriculum**: Step-by-step learning paths progressing from workspace layout and data feeds to quantitative backtesting methodologies and mindset mastery.
  - **Quick Start & Troubleshooting FAQ**: Complete documentation covering account features, cloud preferences synchronization, keyboard shortcuts, and FAQs.

### 8. TrendRadar News
- **Direct Link**: [https://trendradar.nuvexlens.com/](https://trendradar.nuvexlens.com/)
- **Core Features**:
  - **24/7 Global Financial Wire**: Aggregates top-tier financial media, regulatory filings, and market-moving developments.
  - **AI Sentiment & Entity Association**: Semantic categorization that connects incoming news stories with affected industry sectors and individual tickers.
  - **Macro Economic Calendar**: Clear timelines for central bank interest rate meetings, inflation metrics (CPI/PPI), and earnings releases.

---

## Supported Markets & Asset Classes

| Asset Class | Universe Coverage | Data Provided | Ingestion Architecture |
| :--- | :--- | :--- | :--- |
| **China A-Shares** | SSE, SZSE, BSE (All Listed Equities & ETFs) | Real-time quotes, tick prints, historical daily/minute bars, splits & dividend adjustments | Low-latency WebSocket + Dedicated Gateway |
| **US Equities** | NASDAQ, NYSE, AMEX (Full Coverage) | Pre-market, regular hours, after-hours streaming and historical records | International financial data bridges |
| **Hong Kong Equities** | HKEX Main Board & GEM | Real-time tick stream, market depth, and historical OHLCV | Low-latency HK gateway |
| **Cryptocurrencies** | Major Spot & Perpetual Pairs (BTC, ETH, SOL, etc.) | Sub-second pricing, order books, funding rates, open interest | Direct exchange WebSocket infrastructure |
| **Futures & Commodities** | Domestic & Global Benchmark Futures Contracts | Real-time prices and continuous historical contracts | Standardized futures adapter |

---

## Recommended Trader Workflow

1. **Market Context & Top-Down Assessment**:
   - Check the global market pulse on [Market Quotes](https://nuvexlens.com/quotes/).
   - Inspect the [Sector Heatmap](https://nuvexlens.com/quotes/heatmap) to spot sector rotation and leading industries.
2. **Systematic Idea Generation**:
   - Run candidate filters on the [Multi-Market Screener](https://nuvexlens.com/screener/) using preset or customized quantitative parameters.
   - Add shortlisted candidates to your cloud watchlist.
3. **Strategy Alignment & Institutional Confirmation**:
   - Verify if targets match active model recommendations on [Signals Hub](https://chart.nuvexlens.com/signals/hub/strategy).
   - Review [Holdings Tracker](https://chart.nuvexlens.com/signals/hub/holdings) to see whether top funds or smart money are accumulating or distributing.
4. **Execution Timing & Indicator Integration**:
   - Open the candidate in [Smart Chart](https://chart.nuvexlens.com/) to analyze price action across multiple synchronized timeframes.
   - Leverage the [Indicator & Strategy Library](https://docs.nuvexlens.com/indicator-strategies/) for state-of-the-art Pine script execution playbooks, combined with Volume Profile and proprietary indicators to calculate precise risk-reward entry points.
5. **Fundamental & Bottleneck Verification**:
   - Review the panoramic diagnostic on [Stock Analysis](https://chart.nuvexlens.com/signals/analysis) to ensure business fundamentals and moat strength align with your thesis.
6. **Deliberate Practice & Skill Review**:
   - Use the [Replay Trainer](https://chart.nuvexlens.com/) in blind mode on historical setups to sharpen pattern recognition without outcome bias.

---

## Frequently Asked Questions (FAQ)

<details>
<summary><b>Does NuvexLens require a desktop client installation?</b></summary>
<br>
No client download is required. NuvexLens is built entirely on modern web standards and delivers native desktop-tier performance on Chrome, Edge, Safari, and Firefox across Windows, macOS, and Linux.
</details>

<details>
<summary><b>What is the latency of market data updates?</b></summary>
<br>
Streaming quotes and quantitative signals are transmitted via distributed WebSocket clusters with sub-second latency. Historical data and fundamental figures are normalized immediately upon market close.
</details>

<details>
<summary><b>Are watchlists and chart templates synchronized across devices?</b></summary>
<br>
Yes. Once authenticated, your watchlists, chart drawings, indicator templates, and custom screener formulas automatically synchronize securely to the cloud across all your workstations and mobile devices.
</details>

<details>
<summary><b>How does Blind Replay differ from regular historical review?</b></summary>
<br>
Traditional chart scrolling invites severe hindsight bias. NuvexLens Blind Mode obscures the ticker symbol, price scale, and calendar dates, requiring traders to make decisions in simulated real time based strictly on technical evidence.
</details>

---

## Contact & Support

- Official Website: [nuvexlens.com](https://nuvexlens.com)
- Knowledge Base: [docs.nuvexlens.com](https://docs.nuvexlens.com)
- Commercial & Support Inquiries: support@nuvexlens.com

---

<div align="center">

**NuvexLens** — Professional Smart Financial Charting & Analysis

Empowering Professional Trading Decisions

Copyright © 2024-2026 NuvexLens. All Rights Reserved.

</div>
