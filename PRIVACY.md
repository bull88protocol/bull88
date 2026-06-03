# Privacy Policy — Bull88 Protocol

**Last updated: 2026-06-03**

This Privacy Policy explains how the **Bull88 Protocol** application ("the App"),
provided by **CoinTranscend** ("we", "us"), handles your data. We designed the
App to keep your data on your device and under your control.

> Plain-language summary: **We run no servers and collect nothing about you.**
> Your data lives encrypted on your device. The App talks directly to the
> third-party services you connect, using **your own** API keys. An optional
> backup goes to **your own** Google Drive. We never see, collect, or sell your
> data.

## 1. We operate no backend and collect no personal data
The App has **no server of ours**. We do not have a database, we do not receive
telemetry or analytics, and we do not collect, store, or sell any of your
personal or financial information. There is no account with us to create.

## 2. Data stored on your device
The following are stored **locally on your device**, encrypted at rest using
Android's EncryptedSharedPreferences (AES-256):

- Your Charles Schwab API credentials and OAuth tokens.
- Your optional Gemini, FRED, and Finnhub API keys.
- Your trading journal, closed-position ledger, hedge ledger, trigger history,
  watchlist, and app settings.
- The email address of the Google account you select on the lock screen (used as
  a sign-in label and as your backup target — see §4).

These never leave your device except as described below.

## 3. Data you send to third parties (using your own keys)
When you use features that require them, the App connects **directly** from your
device to these third parties, authenticated with **your own** keys/credentials.
We are not a party to these connections:

- **Charles Schwab API** — authentication and market data (e.g., option chains,
  quotes, price history) for the symbols you analyze.
- **Google Gemini API** — the symbol you analyze (sentiment) and your trade
  journal text (the optional AI "Critic"), sent under your own Gemini key.
- **Finnhub API** — the symbol (earnings/dividend calendar), under your own key.
- **FRED API** — macroeconomic data series, under your own key.

Your use of these services is governed by **their** privacy policies and terms.

## 4. Optional Google Drive backup (non-secret data only)
If you choose to use cloud backup, the App uploads a snapshot of your **non-secret
data** — trading journal, closed ledger, hedge entries, trigger history,
watchlist, standing hedge, and climate reports — to **your own Google Drive's
hidden app-data folder**. This space is private to the App and to your Google
account; we have no access to it.

**Your secrets are never backed up:** your Schwab credentials and OAuth tokens
and all API keys stay only on your device and must be re-entered on a new device.
Backup is opt-in (you tap "Back up now") and pinned to the Google account you
signed in with.

## 5. No advertising, no tracking
The App contains no advertising SDKs, no third-party analytics, and no tracking
identifiers used by us.

## 6. Children
The App is not directed to children and is intended for adults managing their own
brokerage accounts.

## 7. Security
Local data is encrypted at rest; all network traffic uses HTTPS. No method of
storage or transmission is 100% secure, and you are responsible for the security
of your device and your accounts.

## 8. Your control
You can delete all local data by clearing the App's data or uninstalling it. You
can delete the Drive backup from your own Google Drive. Removing the App removes
all on-device data.

## 9. Changes
We may update this Policy; the "Last updated" date will change accordingly.

## 10. Contact
Questions: **sunny@bull88protocol.com**.
