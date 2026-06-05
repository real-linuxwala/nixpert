# Nixpert

One-page marketing site for **Nixpert** — live, hands-on online training in:

- **Nutanix** (AOS, Prism, AHV, NCP)
- **VMware** (vSphere 8, ESXi, vCenter, VCP)
- **Linux** (RHCSA path, Bash, systemd)
- **LLM Fundamentals** (RAG, prompting, evals)
- **Anthropic Claude** (Claude API, tool use, agents)
- **OpenAI ChatGPT** (GPT API, function calling, Assistants)
- **Model Context Protocol (MCP)** (servers, tools, integrations)

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

The enrollment form posts via [FormSubmit](https://formsubmit.co); update the
`action` email in `index.html` to receive submissions.
