# HomeTrades — home-trades.com

Marketing homepage for HomeTrades, the AI-powered platform for real estate teams.

## Repository Structure

```
/
├── wrangler.toml          # Cloudflare Pages config
├── public/
│   ├── index.html         # Main homepage
│   └── _redirects         # Cloudflare routing rules
└── README.md
```

## Deploying to Cloudflare Pages

1. Connect this repository to Cloudflare Pages
2. Set build command: `npx wrangler deploy` (or leave blank for static deploy)
3. Set output directory: `public`
4. Deploy

## Local Development

Open `public/index.html` directly in any browser — no build step required.
