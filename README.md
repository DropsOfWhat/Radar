# RADAR — DEX Intelligence Terminal

> See Everything. Trade Instantly.

RADAR is a next-generation DEX intelligence terminal designed to replace DexScreener. It combines real-time token discovery, AI-powered safety scoring, built-in trading, and whale tracking into a single platform.

## Features

- **Real-time Token Tracking** — Live prices, volume, liquidity, and market cap across all major chains
- **AI Safety Score** — Every token gets a 0-100 risk score analyzing LP status, dev wallets, holder distribution, and rug patterns
- **Built-in Trading** — One-click buy/sell with preset amounts, no need to leave the platform
- **Whale Watch** — Track smart money movements in real-time
- **Trend Heatmap** — Visual market momentum at a glance
- **Token Profiles** — Claim and customize your token page with banners, social links, and verified badges
- **Community Fund** — Crowdfunded token profile upgrades by holders

## Deployment

### Vercel (Recommended)

1. Push to GitHub
2. Import repo in [vercel.com](https://vercel.com)
3. Deploy — zero config needed

### Local Development

```bash
npx serve public
```

## Project Structure

```
radar-deploy/
├── public/
│   └── index.html    # Full application
├── package.json
├── vercel.json       # Vercel deployment config
└── README.md
```

## License

All rights reserved.
