# ⚡ Apex-Sweep: 26-Engine Institutional Confluence & Auto-Trade System
**Advanced Multi-Timeframe Smart Money Concepts (SMC) & Algorithmic Confirmation Engine for TradingView (Pine Script v6)**

---

### 1. How a Trade Forms: HTF Zones (OB + GP) & Dual EMA 200/400 Confirmation

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

#### C. Putting It
