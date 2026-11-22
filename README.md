# ⚡ Apex-Sweep: 26-Engine Institutional Confluence & Auto-Trade System
**Advanced Multi-Timeframe Smart Money Concepts (SMC) & Algorithmic Confirmation Engine for TradingView (Pine Script v6)**

---

### 1. HTF Institutional Market Confirmation: Dual EMA Direction & 4H/1D OB/GP Reversals

<img width="1815" height="920" alt="XAUUSD_2026-11-22_23-43-41" src="https://github.com/user-attachments/assets/238b4ae8-1901-4b7a-9c36-c6a663df6a2b" />

#### A. Higher-Timeframe Order Blocks (OB) & Golden Pockets (GP) Only
- **Strict HTF Filtering (Above 15m):** This engine plots Order Blocks and Golden Pockets exclusively from Higher Timeframes (**1H, 4H, and 1D**) — never from noisy lower timeframes.
- **Why HTF Beats LTF:** A `4H` or `1D` zone carries significantly more institutional power than a `15m` or `5m` chart. Whenever price taps into a confirmed `4H` or `1D` OB/GP, lower timeframes (`15m` / `5m`) naturally react with strong, high-momentum reversals. This acts as **Core Confirmation #1**.

#### B. Dual EMA Trend Direction (200 EMA vs. 400 EMA)
To confirm the exact market direction before taking any zone reaction, the engine integrates two color-coded HTF Exponential Moving Averages:
- 🟡 **Yellow Line — `200 EMA` (Initial Directional Confirmation)**
- 🔵 **Blue Line — `400 EMA` (High-Power Institutional Confirmation)**

**Step-by-Step Example (Using the 4H Timeframe):**
1. **Level 1 Confirmation (200 EMA):** When price on the `4H` chart drops below the **Yellow 200 EMA**, the engine registers the first confirmation that market direction has shifted to **SELL**.
2. **High-Power Confirmation (200 + 400 EMA Combined):** When price breaks and stays below **both the 200 EMA and the Blue 400 EMA** across Higher Timeframes (`4H` / `1D`), directional strength multiplies — confirming a **High-Power Sell Bias**.

#### C. Putting It Together (One Core Trade Execution Method)
1. **HTF Direction Locked:** `4H` / `1D` price is trading below both the `200 EMA` (Yellow) and `400 EMA` (Blue) → High-Power Sell direction confirmed.
2. **HTF Zone Tap:** Price retraces and taps into a Higher-Timeframe Sell `OB` or `GP` (`4H` / `1D`).
3. **LTF High-Power Reversal:** With HTF direction and HTF institutional zones fully aligned, the `15m` / `5m` execution chart triggers a sharp, high-probability reversal entry.

---

### 2. Automated Trade Execution: 26-Engine Live Confluence Scoring & Multi-Timeframe Sync

<img width="2752" height="1536" alt="Gemini_Generated_Image_kbql59kbql59kbql" src="https://github.com/user-attachments/assets/042c7626-ff58-4f9b-9f31-ce9cd81aa8b5" />

#### A. The 26-Engine Live Institutional Dashboard
- **Real-Time Confluence Calculation:** Positioned cleanly on the right side of the chart, the system continuously evaluates **26 independent analytical engines** in real time.
- **Dynamic Directional Header:** The top label of the dashboard automatically identifies and displays the active market bias (**BUY** or **SELL**), dynamically scoring how many of the 26 engines align with that exact direction.

#### B. Precision Auto-Entry & Risk Management (`18+ / 26` Threshold)
- **Zero-Emotion Algorithmic Trigger:** The moment the live confluence score hits the institutional threshold (typically **18 / 26 or higher**), the engine automatically executes and plots the trade directly on the chart.
- **Complete Trade Mapping:** Every automated signal comes pre-calculated with exact risk-management levels:
  - 🎯 **Automated Entry Level**
  - 🛡️ **Dynamic Stop Loss (`SL`)**
  - 💰 **Dual Take-Profit Targets (`TP1` & `TP2`)**

#### C. Ultra-High-Confirmation Setup: `15m` + `1H` Simultaneous Alignment
- **Multi-Timeframe Institutional Sync:** When the engine fires automated entries on **both the `15m` and `1H` charts within the same timeline**, it signals an **Ultra-High-Confirmation Setup**.
- **Why `1H` + `15m` Matters:** In institutional trading, the **`1H` timeframe** acts as the critical bridge — it validates the macro **`4H` directional bias** before filtering down to Lower Timeframe (`15m`) execution. When both `1H` and `15m` align simultaneously, trade accuracy and momentum reach peak probability.
