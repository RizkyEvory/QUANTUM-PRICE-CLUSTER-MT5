# Quantum Price Cluster

**Institutional Grade 5-in-1 Trading System for MetaTrader 5**

![MT5 Indicator](https://img.shields.io/badge/Platform-MetaTrader%205-blue)  
![Language](https://img.shields.io/badge/Language-MQL5-orange)  
![Version](https://img.shields.io/badge/Version-3.00-green)  
![Architecture](https://img.shields.io/badge/Architecture-Single%20File-lightgrey)  
![License](https://img.shields.io/badge/License-Protected-red)

## Overview

**Quantum Price Cluster** is a professional, institutional-grade custom indicator that combines **five powerful smart money strategies** into a single, highly efficient file with **zero external dependencies**.

It detects high-probability reversal and continuation zones by analyzing price clustering, order flow, institutional activity, volume profile, and market structure — all in real time.

100% non-repainting signals, premium dashboard, built-in license system, and comprehensive performance tracking.

╔═══════════════════════════════════════════════════════════╗ ║     QUANTUM PRICE CLUSTER - INSTITUTIONAL TRADING SYSTEM   ║ ║                      Version 3.0 Professional              ║ ║                                                             ║ ║  5-IN-1 QUANTUM ENGINE:                                     ║ ║  ├─ Price Cluster Detection                                ║ ║  ├─ Order Flow Imbalance                                    ║ ║  ├─ Institutional Footprint                                 ║ ║  ├─ Volume Profile POC/VAH/VAL                              ║ ║  └─ Market Structure Break                                  ║ ╚═══════════════════════════════════════════════════════════╝

## Features

- **Five Integrated Strategies** working in synergy
- **100% Non-Repainting** signals (confirmed on bar close)
- **Premium Real-Time Dashboard** with all key metrics
- **Smart Price Cluster Detection** (volume-weighted zones)
- **Order Flow Imbalance** analysis (buying/selling pressure)
- **Institutional Footprint** tracking (large volume spikes)
- **Volume Profile** with POC, VAH, VAL calculation
- **Market Structure** analysis (swing highs/lows, trend detection)
- **Built-in License System** (trial + full versions)
- **Performance Analytics** (daily/total signals, bias)
- **Multi-Channel Alerts** (popup, push, email)
- **Zero External Dependencies** – single file architecture

## Visual Elements

| Element              | Symbol/Color                 | Meaning                                    |
|----------------------|------------------------------|--------------------------------------------|
| Buy Signal           | Lime upward arrow (↑)        | High-probability long entry                |
| Sell Signal          | Red downward arrow (↓)       | High-probability short entry               |
| Support Level        | DodgerBlue dotted line       | Combined cluster + institutional support   |
| Resistance Level     | OrangeRed dotted line        | Combined cluster + institutional resistance|
| POC (Point of Control)| Gold dashed line            | Highest volume price level                 |
| Imbalance (internal) | Magenta (hidden buffer)      | Order flow buying/selling ratio            |

## Installation

1. Download `QuantumPriceCluster.mq5`
2. Open MetaTrader 5 → File → Open Data Folder
3. Navigate to `MQL5/Indicators/`
4. Copy the `.mq5` file into this folder
5. Restart MT5 or refresh Navigator
6. Drag onto any chart

## Input Parameters

### Quantum Core Settings
- Cluster Analysis Period
- Volume Profile Lookback
- Market Structure Lookback
- Volume Spike Multiplier
- Minimum Cluster Touches

### Signal Settings
- Enable alerts (popup/push/email)
- Alert cooldown
- Require bar close confirmation

### Display Settings
- Show dashboard
- Show S/R levels and zones
- Custom colors
- Dashboard position

### Risk Management
- Max daily signals
- Minimum signal strength
- Session filtering
- News avoidance (placeholder)

### License System
- License Key (leave empty for trial)
- Trial Mode (enabled by default)

> **Valid License Keys** (for testing/demo):
> - `QUANTUM2024PRO` → Full license
> - `QUANTUM2024DEMO` → 30-day trial
> - `UNLIMITED2024` → Perpetual

## Usage Tips

- Works on all pairs and timeframes
- Best performance on **major forex pairs**, **indices**, and **gold**
- Recommended timeframes: **M15, H1, H4**
- Wait for **arrow signals** + dashboard confluence
- Use dashboard to monitor:
  - Current trend & structure
  - Support/resistance clusters
  - Order flow pressure
  - Institutional bias
- Respect daily signal limit to avoid overtrading

## Author

© Copyright by **M4DI~UciH4**  
GitHub: https://github.com/RizkyEvory

## Disclaimer

This indicator is provided for educational and personal use.  
It includes a license validation system — use only with authorized keys.  
No guarantee of profitability. Trading involves significant risk.  
Use proper risk management and trade responsibly.

---

**Trade like the institutions. See what they see.** 💎
