# ElitHome — FAQ knowledge base

This repo is the **knowledge base for the ElitHome Instagram bot**. The bot reads
every `.md` file in the [`faq/`](faq/) folder and answers customers using only
those facts.

## How to edit
- Open this repo as an **Obsidian vault** (phone or desktop).
- Edit any note in `faq/` — apartments, prices, districts, general info.
- **Commit & push** (Obsidian Git plugin / Working Copy). The bot picks up the
  changes within ~2 minutes — no redeploy needed.

## Rules for good FAQ notes
- One topic/district per file.
- Use clear headings and concrete facts (district, rooms, area m², floor, price, status).
- If a fact isn't written here, the bot will NOT invent it — it'll offer a manager callback.

## Bot config (Railway variables)
- `FAQ_GITHUB_REPO=IkboljonMe/elithome-faq`
- `FAQ_GITHUB_PATH=faq`
- `FAQ_GITHUB_TOKEN=<read-only token>`
