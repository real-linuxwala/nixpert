# Nixpert

One-page marketing site for **Nixpert** — live, hands-on online training in:

- **Linux** (Basics, Advanced, Shell Scripting, Troubleshooting)
- **Infrastructure** (Cloud, Hardware Basics, Hyperconverged, Storage & Networking)
- **Applied AI** (LLMs, RAG, Claude, ChatGPT, Codex, MCP)

We also run custom consulting engagements and accept résumés for open roles.

## Stack

Plain static site — `index.html` + `styles.css`, no build step. Vanilla JS for the
mobile nav and footer year.

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)

1. Push to `main`.
2. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Branch: `main` / root. Save.

## Site behavior

The enrollment form on `index.html` now loads `download.html`, requires name/email/track, and then serves the live courseware PDF.
