## Alexander Komegunov

Senior Salesforce developer. I also build and run automated trading systems on TON, BNB and Robinhood Chain.

---

### Projects

**basisdeck** · delta-neutral DEX → perp arbitrage · live

When a token trades on a DEX below its perpetual price, basisdeck buys it on-chain and opens an equal short on a futures exchange. The profit is the gap between the two prices, so it doesn't depend on which way the market moves. It runs on TON, BNB Chain and Robinhood Chain, hedges on five venues (MEXC, Aster, Gate, BingX, trade.xyz), and includes an operator terminal and a client portal.

`Node.js` `EVM` `TON` `Perps` `Vue` `SQLite`

**TON Arbitrage** · CEX/DEX arbitrage · profitable 1+ year · live clients

Watches TON swaps on STON.fi, DeDust and Tonco and trades them against MEXC. It prices each trade from its own model of the pool, built from on-chain reserves plus pending transactions, instead of relying on DEX APIs that lag. Clients get a dashboard for onboarding and monitoring.

`TON` `STON.fi` `DeDust` `MEXC` `Vue`

**Lighter volume engine** · hedged market making on Lighter + Arcus

Places post-only quotes on Lighter's Robinhood Chain market and hedges each fill right away on Lighter mainnet, across crypto, gold and US stocks. It also holds a small hedged spot position on Arcus. It tracks points earned per $1M of volume from its own fills, not from estimates.

`Lighter` `Robinhood Chain` `Market making` `viem`

**Freepot** · no-loss lottery · Telegram Mini App

Users deposit TON and can withdraw it in full at any time. Each week, the yield from all deposits goes to one winner, drawn on-chain with odds weighted by deposit size.

`Tact` `TON` `React` `Telegram Mini App`

<sub>Also: an atomic MEV backrun bot on Robinhood Chain (Rust), a smart-wallet radar for fomo.family, and [@web3_main](https://t.me/web3_main), a Telegram aggregator for Web3 news.</sub>

---

### Experience

**Senior Salesforce Developer** · Enterprise CPQ · data center industry

I own the customer portal end to end: LWC, Apex and CPQ order flows. I make the architecture decisions and deliver quote-to-order work on schedule.

`LWC` `Apex` `CPQ` `Experience Cloud`

**Salesforce Consultant** · automotive dealer groups, North America

I delivered full Salesforce implementations for several large dealer groups. I gathered requirements, designed the solutions and handed them off to the dev team.

`CRM` `Requirements` `Team lead`

---

[Portfolio](https://sakomg.github.io) · [Salesforce certifications](https://github.com/sakomg/salesforce-certifications)
