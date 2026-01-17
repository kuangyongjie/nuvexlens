<div align="center">

<img src="images/logo.svg" width="100" height="100">

# NuvexLens

**专业级多市场金融图表分析系统**

*基于 TradingView Charting Library 的多数据源智能图表平台*

[![TradingView](https://img.shields.io/badge/TradingView-v28.5-blue?style=flat-square&logo=tradingview)](https://www.tradingview.com/)
[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.100+-009688?style=flat-square&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)](LICENSE)

---

[功能特性](#-功能特性) · [系统架构](#-系统架构) · [快速开始](#-快速开始) · [技术栈](#-技术栈) · [文档](#-文档)

</div>

---

## ✨ 功能特性

<table>
<tr>
<td width="50%">

### 📊 多市场数据支持

- **A 股市场** - 沪深两市全覆盖
- **港股市场** - 港交所实时数据
- **美股市场** - 纳斯达克/纽交所
- **加密货币** - Binance 实时行情
- **期货市场** - 国内主流期货品种

</td>
<td width="50%">

### 🎯 智能数据路由

- **自动识别** - 根据代码智能选择数据源
- **故障转移** - 数据源异常自动切换
- **负载均衡** - 多数据源智能分流
- **实时推送** - WebSocket 毫秒级更新

</td>
</tr>
<tr>
<td width="50%">

### 📈 VIP 专属指标

- **MACD 逃顶抄底** - 智能买卖点提示
- **潮汐脉冲** - 成交量异动检测
- **资金流量剖视图** - 主力资金追踪
- **多维背离检测** - 技术形态识别
- **超级趋势** - 趋势跟踪策略

</td>
<td width="50%">

### 🔄 K线回放训练

- **历史回放** - 任意时间点回放
- **模拟交易** - 无风险策略验证
- **速度控制** - 1x/2x/5x/10x 倍速
- **交易记录** - 完整操作日志

</td>
</tr>
<tr>
<td width="50%">

### 👤 用户系统

- **安全认证** - JWT + Redis Session
- **邮箱验证** - Resend 邮件服务
- **VIP 会员** - 分级权限管理
- **云端同步** - 图表模板 & 自选股

</td>
<td width="50%">

### 🛡️ 代码保护

- **多层混淆** - JavaScript Obfuscator
- **反调试** - 开发者工具检测
- **环境指纹** - 运行时验证
- **虚拟机保护** - 核心逻辑虚拟化

</td>
</tr>
</table>

---

## 🏗️ 系统架构

```
                                    ┌─────────────────────────────────────┐
                                    │         NuvexLens Frontend          │
                                    │     TradingView Charting Library    │
                                    └─────────────────┬───────────────────┘
                                                      │
                                                      ▼
                              ┌────────────────────────────────────────────────┐
                              │              API Gateway (9530)                │
                              │           智能路由 · 负载均衡 · 鉴权           │
                              └────────────────────────┬───────────────────────┘
                                                       │
                 ┌─────────────────────────────────────┼─────────────────────────────────────┐
                 │                                     │                                     │
                 ▼                                     ▼                                     ▼
    ┌────────────────────────┐        ┌────────────────────────┐        ┌────────────────────────┐
    │   Data Sources Layer   │        │   Business Services    │        │   Security Layer       │
    ├────────────────────────┤        ├────────────────────────┤        ├────────────────────────┤
    │ • TuShare     (9528)   │        │ • User Service (9531)  │        │ • Code Obfuscation     │
    │ • AkShare     (9529)   │        │ • Indicator   (9532)   │        │ • Anti-Debug           │
    │ • Binance     (9533)   │        │ • Replay      (9540)   │        │ • VM Protection        │
    │ • TDX         (9534)   │        │ • Pine Script (9536)   │        │ • API Hijack Detect    │
    └────────────────────────┘        └────────────────────────┘        └────────────────────────┘
```

---

## 📡 数据源对比

| 数据源 | 端口 | 市场覆盖 | 数据类型 | 实时推送 | 说明 |
|:------:|:----:|:--------:|:--------:|:--------:|:-----|
| **TDX** | 9534 | A股/港股/期货 | 全周期 | ✅ | 通达信本地数据，速度最快 |
| **TuShare** | 9528 | A股/美股 | 日线+ | ❌ | 专业级数据，需 Token |
| **AkShare** | 9529 | A股 | 分钟级 | ❌ | 免费数据源，无需配置 |
| **Binance** | 9533 | 加密货币 | 全周期 | ✅ | 币安官方 API |

---

## 🚀 快速开始

### 环境要求

- **Python** 3.8+
- **Node.js** 16+ (用于前端构建)
- **Redis** 6+ (可选，用于缓存)

### 一键启动

```bash
# Linux / macOS
chmod +x start-all-services.sh
./start-all-services.sh

# Windows
start-all-services.bat
```

### 手动启动

```bash
# 1. 启动数据网关
cd data-router && python gateway_server.py &

# 2. 启动数据源服务
cd tradingview-tdx-bridge && python tdx_server.py &
cd tradingview-binance-bridge && python binance_server.py &

# 3. 启动业务服务
cd user-service && python server.py &
cd indicator-service && python server.py &

# 4. 启动前端服务
python -m http.server 8080
```

### 访问应用

```
主应用:     http://localhost:8080
用户中心:   http://localhost:9531/static/user/
管理后台:   http://localhost:9531/static/admin/
API 文档:   http://localhost:9530/docs
```

---

## 📊 服务端口

| 服务 | 端口 | 说明 |
|:-----|:----:|:-----|
| **API 网关** | 9530 | 统一入口，智能路由 |
| **用户服务** | 9531 | 认证、权限、会员 |
| **指标服务** | 9532 | VIP 指标计算 |
| **TuShare** | 9528 | A股专业数据 |
| **AkShare** | 9529 | A股免费数据 |
| **Binance** | 9533 | 加密货币数据 |
| **TDX** | 9534 | 通达信数据 |
| **Pine Script** | 9536 | 脚本编译执行 |
| **回放系统** | 9540 | K线回放训练 |

---

## 🛠️ 技术栈

<table>
<tr>
<td align="center" width="20%">

**前端**

</td>
<td align="center" width="20%">

**后端**

</td>
<td align="center" width="20%">

**数据源**

</td>
<td align="center" width="20%">

**基础设施**

</td>
<td align="center" width="20%">

**安全**

</td>
</tr>
<tr>
<td align="center">

TradingView<br>
JavaScript<br>
TypeScript<br>
Webpack

</td>
<td align="center">

FastAPI<br>
Python 3.8+<br>
SQLite<br>
Redis

</td>
<td align="center">

TuShare<br>
AkShare<br>
pytdx<br>
Binance API

</td>
<td align="center">

Nginx<br>
宝塔面板<br>
Cloudflare<br>
SSL/HTTPS

</td>
<td align="center">

JS Obfuscator<br>
JWT Auth<br>
Rate Limiting<br>
Anti-Debug

</td>
</tr>
</table>

---

## 📖 文档

| 文档 | 说明 |
|:-----|:-----|
| [项目结构](开发文档/项目结构20251230.md) | 完整的项目目录说明 |
| [部署指南](开发文档/Linux宝塔面板部署指南.md) | 生产环境部署教程 |
| [VIP 指标开发](开发文档/VIP指标开发文档.md) | 自定义指标开发指南 |
| [数据源开发](开发文档/数据源开发API规范文档.md) | 新增数据源接入规范 |
| [用户系统](开发文档/user-service_用户系统开发文档.md) | 用户认证系统文档 |
| [回放系统](开发文档/回放训练系统开发文档.md) | K线回放功能说明 |
| [Pine 转译器](开发文档/Pine转译器开发指南.md) | Pine Script 编译器 |

---

## 📂 项目结构

```
NuvexLens/
├── 📊 charting_library/          # TradingView 图表库核心
├── 🌐 index.html                 # 主应用入口
├── 🔒 app-core.js               # 前端核心逻辑 (混淆保护)
│
├── 📡 数据源服务
│   ├── data-router/              # API 网关 (9530)
│   ├── tradingview-tushare-bridge/   # TuShare (9528)
│   ├── tradingview-akshare-bridge/   # AkShare (9529)
│   ├── tradingview-binance-bridge/   # Binance (9533)
│   └── tradingview-tdx-bridge/       # TDX (9534)
│
├── 🔧 业务服务
│   ├── user-service/             # 用户服务 (9531)
│   ├── indicator-service/        # 指标服务 (9532)
│   ├── pine-script-service/      # Pine 编译 (9536)
│   └── replay-system/            # 回放系统 (9540)
│
├── 🛡️ 安全模块
│   ├── webpack-obfuscator/       # 代码混淆工具
│   └── advanced-protection-system/   # 高级保护
│
└── 📖 开发文档/                   # 项目文档
```

---

## 📄 许可证

本项目为 **私有软件**，未经授权禁止复制、分发或修改。

Copyright © 2024-2026 NuvexLens. All Rights Reserved.

---

<div align="center">

**NuvexLens** - 专业级多市场金融图表分析系统

Made with ❤️ by NuvexLens Team

</div>
