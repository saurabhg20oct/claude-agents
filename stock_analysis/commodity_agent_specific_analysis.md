---
title: Commodity Agent Specific Analysis
asset_class: Commodity
analysis_type: Agent Specific Analysis
---

## 🎯 Objective
Understand market trends, economic indicators, and company fundamentals in the Indian Commodity Market.

## 📘 Use Cases

### 1. Top Performer Analysis – Infosys Q4 Results
- Infosys beat analyst estimates by 10% in Q4 2024, supported by digital transformation deals and margin improvement.
- Sectors: IT
- Signals: P/E ratio vs peers, earnings momentum

### 2. Worst Performer – Zomato Listing Crash
- Zomato's post-IPO performance declined 40% within 3 months due to unsustainable valuations.
- Signals: Price-to-Sales anomaly, insider lock-in expiry.

### 3. Average Performer – Tata Motors Stable Climb
- Mid-cap recovery based on EV segment optimism and Jaguar Land Rover turnaround.
- Signals: Volume growth, sectoral rotation, improving ROCE.

## ⚠️ Edge Case
- Market overreacted to a false news tweet about RBI rate hike in 2023. Nifty fell 1.5% intraday but reversed.

## 🧠 Claude-style Prompt (YAML)
```yaml
agent_goal: Perform equity market research using Q4 earnings reports of top Nifty 50 firms
data_sources:
  - NSE India earnings calendar
  - Company investor relations
  - Moneycontrol analyst commentary
steps:
  - Identify top and bottom performing stocks post earnings
  - Compare P/E ratio vs industry average
  - Map volume spike with news sentiment
risk_flags:
  - Unusual options activity during earnings week
  - Insider selling pre-announcement
```
