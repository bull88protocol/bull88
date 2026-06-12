# Bull88 Protocol — Beta

**Greed, Optimized.** A premium-selling cockpit for options sellers: HMAI scanner,
CSP/CC journal with a pro-trader roll ladder, hedge ledger, volatility-climate
read, and a monthly analyst report.

> ## ⚠️ This is a one-time public BETA build — read before installing
>
> - This APK is a **beta / testing build**, provided **free** and **as-is**.
> - **Use it entirely at your own risk.** See [TERMS.md](TERMS.md) and
>   [PRIVACY.md](PRIVACY.md) — by installing, you accept them.
> - It is **not** the official release, may contain bugs, and may stop working
>   at any time. **Future updates ship on the Google Play Store version, not
>   here.**
> - The **official Google Play Store version is coming soon** and will receive
>   all future updates and support. This beta will be retired when it launches.
> - This is **not financial or investment advice.** You are solely responsible
>   for your brokerage account, your API keys, and every trade you place.

---

## What it is

Bull88 Protocol is a **bring-your-own-keys** tool: it connects to **your own**
Charles Schwab developer API app and (optionally) your own Gemini, FRED, and
Finnhub keys. Nothing is shipped or shared by us — your credentials and data live
on your device. See [PRIVACY.md](PRIVACY.md) for exactly what is stored where.

## What it does

Bull88 Protocol is a decision-support cockpit for selling options premium —
cash-secured puts (CSPs) and covered calls (CCs). It continuously evaluates your
open positions and watchlist with a **proprietary multi-factor engine** and tells
you, in plain terms, what to do next.

- **Scan** — ranks option candidates per symbol using a composite market-regime
  score (momentum, valuation, fear/greed, signal coherence), tuning how far
  out-of-the-money to sell, the expiration window, and position size to the
  conditions.
- **Manage** — the roll engine scores every open position and surfaces a clear
  **HOLD / ROLL / REVIEW** call. Its priority is simple to state even though the
  exact math isn't published: **capture profit early and cap losses** — roll
  winners to lock gains, and roll defensively to guard against assignment and
  gap-downs, always respecting your cost basis on covered calls.
- **Journal** — a wheel-aware journal tracks every position, roll, and close,
  with cost-basis and realized P/L.

> The factors above are what the engine weighs; the exact thresholds, regime
> bands, and evaluation order are proprietary and intentionally not published.

## Features

- HMAI market-regime scanner for CSP and covered-call candidates (including
  deep-ITM downside-protection writes)
- Proprietary **roll engine** — HOLD / ROLL / REVIEW decisions, with the key
  reason shown on each position
- 5-tier roll taxonomy that prioritizes **capturing profit and capping losses**
- Wheel-aware journal + closed-position ledger with cost-basis tracking
- Hedge ledger (tail-risk insurance) with live evaluation
- Volatility-climate gauge for premium-selling conditions
- Monthly analyst report (positions, P/L, signal history) you can export
- Optional AI trade-journal critic (your own Gemini key)
- Optional encrypted **Google Drive backup** of your data
- Biometric lock · bring-your-own-keys · your data stays on your device

## How it came together

Bull88 Protocol has been built and refined over a long series of iterations. Broadly,
in the order it grew:

- **Core cockpit** — an options scanner with a market-regime score, a cash-secured-put
  journal, biometric lock, and a macro dashboard.
- **Roll engine & taxonomy** — position management that surfaces clear HOLD / ROLL /
  REVIEW calls, with a multi-tier roll taxonomy focused on capturing profit and capping
  losses.
- **Covered calls** — covered-call scanning and journaling, plus pro-trader signal
  triggers (earnings proximity, volatility shocks, momentum shifts).
- **Fundamentals & watchlist** — earnings/dividend awareness, fundamentals lookups, a
  watchlist, and forward-looking forecasts.
- **The wheel, end-to-end** — a wheel-aware state machine with cost-basis tracking
  across assignment and recovery.
- **AI journal critic** — an optional behavioral review of your trade journal (bring
  your own AI key).
- **Risk layer** — concentration awareness, a tail-risk hedge advisor, portfolio-stress
  estimation, and a first-class hedge ledger with live evaluation.
- **Volatility climate** — a premium-selling climate gauge from volatility, breadth, and
  macro inputs.
- **Outcome calibration & reporting** — a signal-outcome ledger that shows how past
  triggers actually resolved, plus an exportable monthly analyst report.
- **Backup & onboarding** — a first-run setup guide and optional encrypted
  backup/restore to your own Google Drive.
- **Public beta** — privacy/IP hardening, a selectable data-source layer, and release
  signing for distribution.

> This reflects the breadth of what's been built over time; the exact strategy
> thresholds, regime bands, and evaluation logic remain proprietary (see *What it does*).

## Requirements

- Android **8.0+** (API 26 or newer).
- Your **own Charles Schwab Developer API** App Key + Secret (the in-app
  "Getting Started" guide walks you through creating them).
- *(Optional, for full features)* your own **Gemini**, **FRED**, and **Finnhub**
  API keys. The app degrades gracefully without them.

## Install (sideloading)

1. Download [**`bull88-protocol-beta.apk`**](bull88-protocol-beta.apk) from this
   repo (open the file and tap **Download**, or use the link).
2. When prompted, allow your browser/file manager to **install unknown apps**
   (Android will warn you — this is normal for any APK installed outside the
   Play Store).
3. Open the APK and tap **Install** → **Open**.
4. On first launch, follow the in-app **Getting Started** guide to add your
   Schwab API credentials.

> **Cloud backup during beta — requesting access.** The optional Google-Drive
> backup is limited to approved testers while the app awaits Google verification.
> To be added, email **sunny@bull88protocol.com** from the Google account you'll
> use, with a one-line note (e.g. *"Requesting Bull88 beta tester access"*).
> Cloud backup becomes available to everyone with the Play Store release; until
> then, an access error just means your account isn't on the tester list yet.

## Latest release

**v1.0.2-beta** — the single newest build is the
[`bull88-protocol-beta.apk`](bull88-protocol-beta.apk) in this repo. Only the
newest beta is supported at a time; see commit history for what changed.

## Support & links

This is an unsupported beta — there's **no guarantee of updates, fixes, or
support**. Issues are appreciated but not guaranteed a response. The supported,
updated version will be the upcoming Play Store release.

- Website: **[www.bull88protocol.com](https://www.bull88protocol.com)**
- Beta tester access / questions: **sunny@bull88protocol.com**

## Legal

- [Terms of Use / EULA](TERMS.md)
- [Privacy Policy](PRIVACY.md)

© CoinTranscend · [www.bull88protocol.com](https://www.bull88protocol.com) ·
"Bull88 Protocol" and related marks are property of CoinTranscend.
