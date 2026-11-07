<div align="center">
  <img src="assets/teapot-mark.svg" width="116" alt="Teapot Router — a clay seal with a forest-green teapot" />
</div>

<h3 align="center">Teapot Router</h3>

<p align="center">
  <strong>Stability-first AI gateway for Claude Code and GPT.</strong><br/>
  One key, both protocols. Pay-as-you-go. Balance never expires.
</p>

<p align="center">
  <a href="https://teapotrouter.com">Website</a> ·
  <a href="https://teapotrouter.com/en/docs">Docs</a> ·
  <a href="https://teapotrouter.com/api/pricing">Pricing JSON</a> ·
  <a href="https://teapotrouter.com/en/status">Status</a>
</p>

---

This is the **official operating account** of [Teapot Router](https://teapotrouter.com).
Development and community live in the **[teapot-router](https://github.com/teapot-router)** organization:

- **[teapot-router](https://github.com/teapot-router/teapot-router)** — gateway overview, connect guides
- **[teapot-router-config](https://github.com/teapot-router/teapot-router-config)** — two-line config templates for Claude Code / OpenAI SDK
- **[llm-api-gateway](https://github.com/teapot-router/llm-api-gateway)** — LLM API gateway for coding agents
- Multilingual landing repos: [ja](https://github.com/teapot-router/teapot-router-ja) · [ko](https://github.com/teapot-router/teapot-router-ko) · [es](https://github.com/teapot-router/teapot-router-es) · [fr](https://github.com/teapot-router/teapot-router-fr) · [pt](https://github.com/teapot-router/teapot-router-pt)

## Connect in two lines

```bash
# Claude Code
export ANTHROPIC_BASE_URL="https://api.teapotrouter.com"
export ANTHROPIC_AUTH_TOKEN="rl_your_token"
```

```python
# OpenAI SDK / Codex
client = OpenAI(
  base_url="https://api.teapotrouter.com/v1",
  api_key="rl_your_token",
)
```

## Brand assets

| File | Use |
|---|---|
| [`assets/teapot-mark.svg`](assets/teapot-mark.svg) | Compact mark — clay seal, forest-green teapot |
| [`assets/teapot-avatar-orange.png`](assets/teapot-avatar-orange.png) | Avatar, orange background (1024×1024) |
| [`assets/teapot-avatar-green.png`](assets/teapot-avatar-green.png) | Avatar, favicon style (1024×1024) |
| [`assets/social-preview.png`](assets/social-preview.png) | Social preview banner (2560×1280) |

---

<p align="center">
  <sub>Named after HTTP <b>418 “I'm a teapot”</b> 🫖 — a teapot doesn't grow tea, it pours it. <a href="https://teapotrouter.com/zh/418">RFC 2324</a></sub>
</p>
