# FlashPerp — 60 Second Demo Script
## Screen Recording Guide

---

### SETUP (before recording)
- Anvil running in terminal (`anvil --chain-id 31337 --port 8545`)
- Contracts deployed, pool seeded with $500k
- MetaMask connected to Anvil Local (Chain ID 31337)
- Anvil account imported with 10,000 ETH
- Browser open at `http://localhost:8080/index.html`
- Screen resolution: 1440x900 or higher
- Use Loom, QuickTime, or OBS

---

### SCENE 1 — Landing Page (0:00 – 0:08)
**Screen:** index.html landing page
**Action:** Slowly scroll down past the hero — show live BTC/ETH/SOL prices loading
**Voiceover:**
> "FlashPerp — the first flash liquidity perpetual protocol.
> No collateral. Positions settle in minutes, not days."

**Key visual:** Live prices ticking, "Testnet Live · Arbitrum" badge

---

### SCENE 2 — Launch App (0:08 – 0:14)
**Screen:** Click "Launch App" → War Room UI loads
**Action:** Pause on the War Room for 3 seconds — let the chart animate
**Voiceover:**
> "The War Room. Real-time price feed, live pool stats,
> and a full order panel — all in one screen."

**Key visual:** Grid background, green chart ticking, pool stats loading

---

### SCENE 3 — Connect Wallet (0:14 – 0:22)
**Screen:** Click "Connect" → MetaMask popup
**Action:** Approve connection, show wallet address appearing in header
**Voiceover:**
> "Connect your wallet. Pool stats load instantly —
> $500,000 in liquidity, ready to back your trade."

**Key visual:** TVL $500,000, Available $470,001, Utilisation 6% all appearing

---

### SCENE 4 — Mint Test USDC (0:22 – 0:28)
**Screen:** Click "Mint 10,000 Test USDC"
**Action:** Confirm MetaMask, show USDC balance update in header
**Voiceover:**
> "On testnet, mint USDC instantly to trade with.
> No faucet hunting, no waiting."

**Key visual:** "Your USDC" updating to $10,000 in the status bar

---

### SCENE 5 — Open a Position (0:28 – 0:48)
**Screen:** Order panel on the right
**Action:**
1. Click LONG (green highlights)
2. Type "1000" in borrow amount
3. Select 5x leverage
4. Select 5min duration
5. Show summary box calculating — notional $5,000, liq price, max profit
6. Click "⚡ Execute Long"
7. Confirm MetaMask
8. Show position appearing in the table with countdown timer

**Voiceover:**
> "Borrow $1,000. Five times leverage. Five minute window.
> No collateral required — the pool backs the trade.
> One click. Position is live."

**Key visual:** Position row appearing — LONG badge, countdown timer ticking from 05:00

---

### SCENE 6 — Watch It Live (0:48 – 0:54)
**Screen:** Center panel — chart + position table
**Action:** Let the chart tick for a few seconds, watch P&L update in real time
**Voiceover:**
> "P&L updates in real time. The countdown is running.
> At zero — it auto-settles. No action required."

**Key visual:** P&L number changing colour, timer counting down

---

### SCENE 7 — Close Early (0:54 – 1:00)
**Screen:** Click "Close" on the position
**Action:** Confirm MetaMask, show position disappearing, pool stats updating
**Voiceover:**
> "Close early or let it expire — your choice.
> FlashPerp. Borrow. Trade. Settle."

**Key visual:** Position row disappearing, available liquidity increasing

---

### POST-PRODUCTION TIPS
- Add text overlays for key stats (TVL, leverage, duration)
- Highlight the countdown timer in scene 6 with a zoom
- Add subtle background music — something tense, minimal
- End card: "FlashPerp Testnet — flashperp.xyz — Join Discord"
- Total target: 55–65 seconds

---

### TWITTER POST COPY (to accompany the video)
```
Built @FlashPerp in public 🧵

The first flash liquidity perp protocol:
→ No collateral required
→ Borrow from pool, trade, auto-settle
→ 1 minute to 1 hour positions
→ Up to 10x leverage
→ Anyone can create a market

Testnet live on Arbitrum.

[video]

Docs → flashperp.xyz
```

---

### ALTERNATIVE 30-SECOND CUT
If you want a shorter version for TikTok/Reels:
- Scene 1: 0:00–0:03 (landing page, 3 secs)
- Scene 3: 0:03–0:08 (connect wallet, 5 secs)
- Scene 5: 0:08–0:22 (open position, 14 secs)
- Scene 6: 0:22–0:28 (watch P&L live, 6 secs)
- Scene 7: 0:28–0:30 (close, end card, 2 secs)
