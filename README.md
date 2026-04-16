# VentureUp PH 🚀

> AI-powered business advisor for Filipino entrepreneurs

A single-page web app that helps young Filipinos start and grow their businesses with an AI advisor, curated resources, learning modules, and a business dashboard.

## Features

- 🤖 **AI Business Advisor** — Ask business questions, get PH-specific advice
- 📊 **Dashboard** — Track your business journey and KPIs
- 📚 **Learn** — Curated lessons on starting and growing a PH business
- 🔗 **Resources** — Tools, templates, and guides for Filipino entrepreneurs
- 💳 **Credits system** — Freemium model with GCash/Maya payment flow (demo)

## Tech Stack

- Vanilla HTML, CSS, JavaScript (zero dependencies)
- Anthropic Claude API for AI advisor
- Google Fonts (Bricolage Grotesque, JetBrains Mono)

## Deployment

This project is deployed on [Vercel](https://vercel.com) via GitHub.

### Run locally

```bash
npx serve .
```

Then open `http://localhost:3000`.

## ⚠️ API Key Note

The AI Advisor uses the Anthropic Claude API. Because this is a frontend-only app, the API key is **not** embedded in the code — the app will call the Anthropic endpoint directly from the browser. Make sure you handle API key exposure carefully before going to production.

---

Made with ❤️ for Filipino entrepreneurs.
