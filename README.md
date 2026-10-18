## Pranay Gaurav

I build **trading execution systems** — software that turns a trading idea into orders that
actually reach a venue, and the tests that prove it behaves before real money moves. Rust and
C++20 engines, order books, market-making platforms and venue adapters, written from
measurement rather than documentation.

**Where I trade:** sports betting exchanges and prediction markets (Polymarket, Kalshi,
Smarkets), crypto spot and perpetuals, DeFi and memecoin liquidity onchain, and traditional
markets — forex, NSE options and equities, NASDAQ and ES futures, and SPX options through IBKR.

**How I work:** paper first, with live order paths gated behind explicit risk checks. Research
is reported as measured, including when the answer is no — one market-making study on real
Kalshi data finds that spread capture does not pay, and that result stays in rather than being
tuned away.

**Investing:** portfolio construction across equities and real estate, plus a crypto portfolio
system that is still a design specification.

Early-stage work stays public instead of hidden, and every repository that is in development
or design-only says so at the top of its page — a profile is only useful if you can tell the
difference.

---

### Trading and Investing

| Category | Portfolio | What's in it |
|---|---|---|
| 🏇 **Sports Betting** | **[Algorithmic Sports Betting](https://github.com/pranay123-stack/algorithmic-sports-betting)** | Hub — exchange arbitrage, outcome modelling and staking across football, basketball and horse racing |
| | **[Horse Racing Quant Platform](https://github.com/pranay123-stack/horse-quant-platform)** | UK racing — point-in-time features, calibrated probability models, EV staking, walk-forward backtests |
| | **[Smarkets Sports Quant Trading](https://github.com/pranay123-stack/Smarkets_Sports_Quant_Trading)** | Quantitative strategies on the Smarkets betting exchange |
| | **[Kalshi Sports RFQ Combo Pricing](https://github.com/pranay123-stack/kalshi-rfq-combo-pricing-engine)** | Multi-leg sports parlay pricing — Gaussian copula fitted on real settled games, paper market making |
| | **[Kalshi Sports RFQ Market Maker](https://github.com/pranay123-stack/kalshi-rfq-market-maker-volume-optimizer)** | Adverse selection measured against real settlements — finds spread capture does not pay; 977 tests |
| | **[NBA Prediction Edge](https://github.com/pranay123-stack/nba-prediction-edge)** | NBA Playoffs — injury-driven signals with cross-market momentum lag on Polymarket |
| | **[MatchCall](https://github.com/pranay123-stack/matchcall)** | World Cup prediction market on Solana, settled onchain via SPL escrow |
| | **[FairPlay Onchain Sportsbook](https://github.com/pranay123-stack/fairplay-onchain-sportsbook)** | Fully-collateralised sports betting on Ethereum — Solidity, indexer, Next.js |
| 🎯 **Prediction Market** | **[Prediction Market Algorithmic Trading](https://github.com/pranay123-stack/prediction-market-algorithmic-trading)** | Hub — Polymarket execution research, copy trading, Kalshi integration, an onchain pari-mutuel protocol |
| | **[Polymarket Live CLOB Research](https://github.com/pranay123-stack/polymarket-live-clob-research)** | Rust — replays real Polymarket data to find where theoretical edge disappears under real execution |
| | **[Polymarket Copy-Trading Engine](https://github.com/pranay123-stack/polymarket-copy-trading-hft-rust)** | Rust — paper and live behind one adapter seam; 341 tests, 0 unsafe |
| | **[Kalshi BTC Integration](https://github.com/pranay123-stack/kalshi-btc-integration)** | Paper-first Kalshi execution layer for a BTC bot — order translation, idempotent submission, reconciliation |
| 🦄 **DeFi Trading** | **[DeFi Algorithmic Trading](https://github.com/pranay123-stack/defi-algorithmic-trading)** | Hub — onchain execution against DEX liquidity and the protocols it trades against |
| | **[Hook Explorer](https://github.com/pranay123-stack/hook-explorer)** | Uniswap v4 pre-trade risk — decodes what a hook may do to your swap; 383+ tests, Playwright in CI |
| | **[Delta-Neutral Yield Vault](https://github.com/pranay123-stack/delta-neutral-yield-vault)** | ERC-4626 basis trade — lending long + perp short, keeper rebalancer, PnL reconciled to NAV |
| ⚡ **DeFi HFT** | **[Uniswap Mempool Sniper](https://github.com/pranay123-stack/web3-projects)** | Six-agent mempool bot — pending-tx watch, new-pool detection, pre-buy safety gate, execution |
| ₿ **Crypto Trading** | **[Crypto Trading Strategies](https://github.com/pranay123-stack/crypto-trading-strategies)** | Hub — statistical arbitrage, ICT smart-money and mean reversion across Binance, Phemex, HyperLiquid |
| | **[Crypto Algorithmic Trading Projects](https://github.com/pranay123-stack/Algorithmic-Trading-Projects)** | 20+ strategies — backtesting engines, paper-trading systems and live bots |
| | **[Crypto Medium-Frequency Trading](https://github.com/pranay123-stack/crypto-medium-frequency-Algorithmic-trading)** | 1s–15m timeframe system with backtesting and multi-exchange support |
| | **[Perp Funding & Basis Arbitrage](https://github.com/pranay123-stack/perp-funding-basis-arb)** | Delta-neutral cross-exchange carry — cost model, portfolio optimiser, multi-leg execution; paper only, 484 tests |
| | **[Delta Exchange Crypto Trading](https://github.com/pranay123-stack/delta-exchange-crypto-algorithmic-trading)** | Perpetual ↔ MT5 cross-venue hedging — inverse-contract delta, two-leg execution with recovery |
| | **[Crypto ICT Pine Strategies](https://github.com/pranay123-stack/Tradingview_Pinescript_Strategy)** | Non-repainting Pine v6 — ICT liquidity sweep reversal and volume-profile continuation |
| 🏎️ **Crypto HFT & Market Making** | **[Crypto Market-Making Engine](https://github.com/pranay123-stack/crypto-mm-engine)** | C++20 MM execution platform — exchange-agnostic core, shared paper/live engine, authoritative risk |
| | **[Crypto HFT Market Making System](https://github.com/pranay123-stack/crypto-hft-market-making-system)** | C++, Rust and Python MM bot templates — single- and multi-exchange |
| | **[Crypto Exchange Development](https://github.com/pranay123-stack/crypto-exchange-development)** | Order books, matching engines, venue simulators and exchange-agnostic connectivity |
| 🐸 **Memecoin Trading** | **[Memecoin Algorithmic Trading](https://github.com/pranay123-stack/memecoin-algorithmic-trading)** | Mempool sniping with onchain safety screening, and pump.fun-style launchpad mechanics |
| 💼 **Crypto Investment Portfolio** | **[Crypto Portfolio AI System](https://github.com/pranay123-stack/crypto-investment-management-portfolio-ai-system)** | LSTM/Transformer prediction, RL allocation, auto-rebalancing — design spec, not implemented |
| 📈 **Trading** | **[Forex Trading Strategies](https://github.com/pranay123-stack/forex-trading-strategies)** | MQL5 Expert Advisors with custom parametric oscillators and Strategy Tester reports |
| | **[TradingView Pine Script](https://github.com/pranay123-stack/tradingview-pinescript)** | Non-repainting ICT strategies with written repainting audits, futures scripts, ES indicator toolkit |
| | **[ATAS & Order Flow](https://github.com/pranay123-stack/atas-orderflow-scripts)** | Tape speed and range bars — Pine implementations of ATAS order-flow concepts |
| | **[NSE Option Trading Strategies](https://github.com/pranay123-stack/nse-options-strategies)** | NIFTY/BANKNIFTY F&O — put-call parity arbitrage, ICT options scalping via Kite and XTS |
| | **[NSE Equity Trading Strategies](https://github.com/pranay123-stack/nse-equity-strategies)** | Intraday systematic entries on NIFTY 50 and F&O-eligible stocks |
| | **[NASDAQ Futures Trading Strategies](https://github.com/pranay123-stack/nasdaq-futures-strategies)** | NQ/MNQ intraday ICT and opening-range execution through IBKR TWS |
| | **[ES Futures Trading Strategies](https://github.com/pranay123-stack/es-futures-strategies)** | E-mini S&P 500 breakout and ICT structure, TradingView Pine into IBKR |
| | **[SPX & SPY Trading Strategies](https://github.com/pranay123-stack/spx-spy-strategies)** | 0DTE and short-dated index options — credit spreads, iron condors, butterflies via IBKR TWS |
| | **[Interactive Brokers (IBKR) Trading Bots](https://github.com/pranay123-stack/ibkr-trading-bots)** | Live SPX options automation on the TWS API — 3 published engines, credentials and client data removed |
| | **[NASDAQ Equity Trading Strategies](https://github.com/pranay123-stack/nasdaq-equity-strategies)** | Systematic single-name US equity work — in development |
| | **[Taiwan HFT Trading Strategies](https://github.com/pranay123-stack/taiwan-hft-strategies)** | Low-latency trading on TWSE and TAIFEX — in development |
| | **[ASX Trading Strategies](https://github.com/pranay123-stack/asx-trading-strategies)** | Australian Securities Exchange systematic trading — in development |
| | **[Algo Trading Competitions](https://github.com/pranay123-stack/algo-trading-competition)** | Agent arenas, prop-firm evaluations and quant tournaments |
| | **[Algo Trading Hackathons](https://github.com/pranay123-stack/algo-trading-hackathons)** | Trading-mechanic hackathon projects with verifiable outcomes |
| 🏦 **Investment** | **[Investment Management](https://github.com/pranay123-stack/investment-management)** | Portfolio construction across equities and real estate |

### Creative Tech Ideas

Product concepts of my own, in development. Each says plainly what is built and what
is only scoped — none is presented as shipped.

| | Portfolio | What's in it |
|---|---|---|
| 🗂️ | **[Administrative App](https://github.com/pranay123-stack/administrative-app)** | High-stakes performance management — ratings driving reward and retention, with audit and appeal paths |
| 💘 | **[Dating App](https://github.com/pranay123-stack/dating-app)** | Matching, discovery, trust & safety — in development |
| 🎉 | **[Home Party App](https://github.com/pranay123-stack/home-party-app)** | Group event hosting — a working non-custodial shared-cost pot, wider product in development |
| 📚 | **[Group Study App](https://github.com/pranay123-stack/group-study-app)** | Collaborative learning — built on real Rust and low-latency C++ curriculum; app in development |

### Competitor Tech Apps

Reimplementations of established consumer platforms — chosen because rebuilding a
product at scale is the fastest way to meet the problems its engineers solved.

| | Portfolio | What's in it |
|---|---|---|
| 📘 | **[Facebook App](https://github.com/pranay123-stack/facebook-app)** | Social platform — feed ranking, social graph, read-time privacy enforcement; in development |

### Creative Field

Writing across long-form, screen and live formats. All of it is in development, and each
entry says so — none is presented as published work.

| | Portfolio | What's in it |
|---|---|---|
| 🧠 | **Philosophy Writing** | Essays and long-form philosophical writing — in development, not yet published |
| 📖 | **[Novel Writing](https://github.com/pranay123-stack/novel)** | Long-form fiction — structure, drafting and revision; in development |
| 🎬 | **[Film Writing](https://github.com/pranay123-stack/ott-film-writing)** | Feature and short-film screenwriting — structure published, scripts not yet released |
| 📺 | **[Web Series Writing](https://github.com/pranay123-stack/ott-film-writing)** | OTT series development — episode arcs and season structure; in development |
| 🎤 | **Reality Shows Writing** | Format writing for live reality shows — rounds, contestant arcs, show-day scripting; in development |

### Ventures

| | Portfolio | What's in it |
|---|---|---|
| 🚀 | **[Startup & Fundraising](https://github.com/pranay123-stack/startup-and-fundraising)** | Grant applications, investor materials, and the tested systems behind them |

---

### A note on how I present work

Each portfolio separates **what has been independently executed** from what a repository
reports about itself, and self-declared limitations are preserved rather than hidden — if a
system says it is at phase 10 of 16, that line stays in.

Where a README's numbers didn't match the code, I corrected them in both directions: one
project claimed 91 end-to-end tests and has 68; another claimed 230 and has 269.

Repositories that contain a design document and no implementation say so in a banner at the
top, and are never listed as built work.

If you want to check something rather than take my word for it, every featured project
lists the clone-and-run command that reproduces its numbers.

All repositories are mapped in **[the complete repository map](./PORTFOLIO-MAP.md)** —
every one labelled as built code, a design specification with no implementation, or
learning/archived work.

---

**Working in:** Rust · C++20 · TypeScript · Python · Solidity · Go

📫 pranaygaurav4555@gmail.com
