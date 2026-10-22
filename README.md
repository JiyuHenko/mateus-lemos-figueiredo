# Mateus Lemos Figueiredo — Portfolio

A personal portfolio for **Mateus Lemos Figueiredo** (also known as **Jiyu Henko**), focused on applied AI, developer tooling, test automation, software engineering and client-facing delivery.

**Website:** https://jiyuhenko.github.io/mateus-lemos-figueiredo/

## Selected work

- **Violet (2024):** a tool-using AI assistant prototype with browser automation, persistent context, observed tool results and human approval.
- **E2E Guard (2026):** a Go developer tool to identify structural issues and conventions in automated test suites.
- **Agentic SDLC Reference:** engineering practices for safer and more verifiable coding-agent workflows.
- **Custom Mind:** software and automation work with clients across industries.

Some projects and implementations are private. Public explanations focus on the relevant architecture, decisions and evidence rather than exposing client work.

## A little playground

The home page includes three small interactive sketches:

1. **Violet:** move through a simulated tool request and approve or deny the action.
2. **E2E Guard:** try a lightweight JavaScript test checker with editable examples.
3. **Agentic SDLC:** compare fast iteration checks with fuller release evidence.

These are **educational, browser-only simulations**, not live integrations, real filesystem tools, or the production E2E Guard engine. They make no network calls or external API requests.

## Run locally

This is a static website with **no build step and no runtime dependencies**.

```sh
python3 -m http.server 8000
```

Open http://localhost:8000/ in your browser.

- Homepage: `index.html`
- Design system: `assets/css/warm.css`
- Demo interactions: `assets/js/demos.js`
- Technical-case layout: `assets/css/portfolio-v2.css`
- Case studies: `cases/violet.html` and `cases/agentic-sdlc.html`

## Links

- GitHub: https://github.com/JiyuHenko
- LinkedIn: https://www.linkedin.com/in/jiyu-henko-539253332/
- Custom Mind: https://www.custommind.com.br/
- Email: mateusllemosf@gmail.com
