# CoreForge Collector 4

VPN configs **verified live from inside Iran** 🇮🇷.

## Subscription

- **Base64:** `https://raw.githubusercontent.com/paranoideveloper/CoreForge-Collector4/main/subscription_base64.txt`
- **Plain text:** `https://raw.githubusercontent.com/paranoideveloper/CoreForge-Collector4/main/subscription_raw.txt`

Add the base64 URL to any client (v2rayNG, NekoBox, Hiddify, Streisand, …). Each config is named `<flag> CoreForge 4 NNN`, where the flag is the exit country and `NNN` is the speed rank (001 = fastest).

## Latest run (2026-10-18)

| Stage | Count |
|---|---|
| Scraped pool (fresh) | 31,872 |
| Testable (vless/vmess/trojan/ss) | 31,251 |
| Unique backends after dedup | 16,089 |
| Tunnel-tested from Iran | 4,000 |
| **Verified working from Iran** | **5** |

Working set: 4 × VLESS, 1 × VMess. Exit countries: 🇬🇧 GB, 🇰🇷 KR, 🇨🇦 CA (+ 2 Iran-internal).

A low pass rate is expected and honest — most publicly-shared configs do **not** survive Iran's filtering. The handful that do are what you see here.

## Method

1. A pool is scraped from public sources (GitHub + Telegram mirrors + subscriptions).
2. The pool is shipped to an in-country vantage.
3. From there: a TCP-reachability prefilter, then a full proxy test per survivor (spin up the tunnel, download through it, measure throughput).
4. Survivors are deduped, speed-ranked, tagged, and published here.

*These are third-party public configs, not operated by this project — they can stop working at any time. Refreshed on each run.*
