<div align="center">
  <a href="https://cloudbit.to">
    <img src="https://raw.githubusercontent.com/Cloudbit-Global/core/main/assets/cdbc-logo-256.png" alt="Cloudbit Classic ($CDBC) Bot Logo" width="130" height="130" />
  </a>
  <h1>Cloudbit Classic Telegram Bot &amp; Mini App (<code>@cloudbit_ai_bot</code>)</h1>
  <p><strong>Official Tap2Earn, GameFi &amp; Community Engagement Portal for Cloudbit Classic ($CDBC)</strong></p>
  <p>
    <a href="https://t.me/cloudbit_ai_bot">Launch @cloudbit_ai_bot</a> &bull;
    <a href="https://cloudbit.to">cloudbit.to</a> &bull;
    <a href="https://cdbc.io">cdbc.io</a> &bull;
    <a href="https://cloudbitex.com">cloudbitex.com</a> &bull;
    <a href="https://x.com/cloudbit_">X (@cloudbit_)</a>
  </p>
</div>

---

## Overview

`cdbc-bot` is the official Telegram Mini App (TMA) and GameFi interface for **Cloudbit Classic ($CDBC)**. Designed for high-speed mobile interaction inside Telegram, `@cloudbit_ai_bot` enables community members to mine points, complete ecosystem quests, invite referrals, and connect directly with the `$CDBC` multichain infrastructure.

### Core Features
* **Tap2Earn & Mining Engine:** Interactive mobile WebApp interface optimized for instant Telegram WebView rendering.
* **Referral & Community Quests:** Multi-tier invite tracking and verified social tasks across `cdbc.io`, `cloudbitex.com`, X (`@cloudbit_`), and Instagram (`@cloudbit.official`).
* **Ecosystem Synchronization:** Direct integration with the public `$CDBC` supply endpoints (`https://cdbc.io/api`) and verified multichain contract registry.
* **Zero-Telemetry Privacy Architecture:** Built without third-party tracking pixels or invasive analytics scripts.

---

## Tokenomics & Verified Contract Reference

| Parameter | Specification |
| :--- | :--- |
| **Token Name** | Cloudbit Classic |
| **Ticker** | CDBC (`$CDBC`) |
| **Total Supply** | `200,000,000 CDBC` (Fixed Maximum Supply) |
| **Buy / Sell Tax** | `0% Buy Tax / 0% Sell Tax` |
| **Primary Network** | BNB Smart Chain (BEP-20) |
| **Main Contract (BSC)** | `0xaf8b1b1bb4a47f537932968C7DE6E251dd50C6a9` |
| **Official Bot Handle** | [`@cloudbit_ai_bot`](https://t.me/cloudbit_ai_bot) |
| **Short Link Hub** | [`https://cloudbit.to`](https://cloudbit.to) |

---

## Environment Configuration

Copy `.env.example` to `.env` before running local Mini App previews or webhook tests:

```bash
cp .env.example .env
```

> **Security Notice:** Never commit live bot tokens, database credentials, or production signing keys to public repositories. Production backend workers and anti-sybil verification services remain isolated in private infrastructure.

---

## Official Ecosystem Repositories
* **[`Cloudbit-Global/core`](https://github.com/Cloudbit-Global/core)** – Multichain contract registry, verified ABIs, and official brand assets.
* **[`Cloudbit-Global/cdbc-app`](https://github.com/Cloudbit-Global/cdbc-app)** – Web3 portal interfaces (`cdbc.io` & `cloudbitex.com`).
* **[`Cloudbit-Global/cdbc-api`](https://github.com/Cloudbit-Global/cdbc-api)** – Public supply endpoints and OpenAPI 3.1 specifications (`cdbc.io/api`).