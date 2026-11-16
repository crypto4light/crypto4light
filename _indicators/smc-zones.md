---
title: SMC Zones
description: Explore the Crypto4light SMC Zones TradingView indicator. Learn how
  to identify and analyze smart money concepts zones and potential market
  reaction areas.
permalink: /indicators/smc-zones/
access: FREE
keywords:
  - SMC Zones
  - Smart Money Concepts Indicator
  - TradingView SMC Indicator
  - Supply and Demand Zones
  - Crypto Market Structure
image: /assets/images/uploads/smc.jpg
youtube_id: jtCcsD-HBVc
layout: indicator
order: 4
tradingview_url: https://www.tradingview.com/script/mtvitujX-Crypto4light-SMC-Zones/
---
## Crypto4light SMC Zones – Minimalist Market Structure Overlay

Crypto4light SMC Zones is a minimalist market structure overlay inspired by Smart Money Concepts (SMC). It is designed to reduce chart noise while keeping essential structural information clearly visible.

The indicator focuses on four key components: Fair Value Gaps (FVG), body-based Order Blocks (OB), Break of Structure (BOS), and Buyside/Sellside Liquidity.

## What the Indicator Displays

* **Fair Value Gaps (FVG)** – Bullish and bearish imbalance zones with a 50% midpoint.
* **Order Blocks (OB)** – Bullish and bearish zones calculated using candle bodies only.
* **Break of Structure (BOS)** – Confirmed structural breaks based on pivot highs and lows.
* **Liquidity Levels** – Buyside and sellside liquidity identified through equal highs and equal lows.

## Core Logic & Settings

### Fair Value Gaps

* FVGs are detected exclusively on the current chart timeframe.
* Bullish and bearish gaps are displayed as colored zones.
* Each FVG includes a 50% midpoint line.
* Customizable mitigation behavior:

  * **50% Mid** – Default setting; considers the gap mitigated when price reaches its midpoint.
  * **Wick Full** – Uses the candle wick reaching the full gap boundary.
  * **Close Full** – Uses a candle close beyond the full gap boundary.

### Order Blocks

Order Blocks are drawn using candle bodies only, without extending zones to include wicks.

This approach keeps the zones tighter and avoids unnecessarily large areas on the chart, helping maintain a cleaner market structure view.

### Break of Structure

BOS detection is based on confirmed pivot structure. This provides a structured approach to identifying breaks of significant swing highs and lows.

### Liquidity

Buyside and sellside liquidity are identified using equal highs and equal lows. A configurable tolerance threshold allows you to adjust how closely price levels must match to qualify as liquidity.

## Alerts & Notifications

The indicator includes separate alerts for the following events:

* Bullish FVG Touch
* Bearish FVG Touch
* Bullish FVG 50% Touch
* Bearish FVG 50% Touch
* Bullish OB Touch
* Bearish OB Touch
* Bullish BOS
* Bearish BOS
* Buyside Liquidity Sweep
* Sellside Liquidity Sweep

## Minimalist Design Philosophy

The goal of Crypto4light SMC Zones is simple: **keep the chart clean while preserving the market structure information that matters.**

Instead of filling the chart with oversized zones, excessive labels, and unnecessary visual elements, the indicator focuses on essential levels and structural events.

Every visual element has a purpose, making it easier to analyze price action without unnecessary distractions.

## Important Notes

* The indicator uses confirmed pivot-based structure. As a result, some elements appear with a confirmation delay by design.
* FVG detection is limited to the current chart timeframe.
* Alert behavior and zone persistence depend on the selected mitigation and cleanup settings.
* Crypto4light SMC Zones is a market structure visualization tool, not a standalone trading system.

**It's not magic. It's a tool to work with.**

Use it as part of your own technical analysis and always apply proper risk management.
