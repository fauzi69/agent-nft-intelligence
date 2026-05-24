# NFT Market Intelligence Architecture

## Purpose

Collection intelligence product for holder quality, floor pressure, trait momentum, and liquidity alerts.

## Runtime loop

1. **Observe** — collect domain signals: floor_depth, unique_holder_ratio, trait_velocity, listing_pressure, whale_accumulation.
2. **Orient** — map the active scenario to specialist agent responsibilities.
3. **Decide** — score severity, confidence, and operator urgency.
4. **Act** — emit next actions that a human operator can verify.
5. **Reflect** — attach trace IDs and deterministic evidence for review.

## Components

- `backend/swarm.py` — pure Python reasoning core, safe for CI and static demos.
- `backend/app.py` — FastAPI wrapper for product integration.
- `cli.py` — terminal demo path for reviewers.
- `index.html` — front-facing dashboard surface.

## Agent responsibilities

- `Collection Health Analyst`: owns one part of the analysis loop.
- `Trait Momentum Scout`: owns one part of the analysis loop.
- `Holder Quality Scorer`: owns one part of the analysis loop.
- `Liquidity Pressure Agent`: owns one part of the analysis loop.
- `Drop Strategy Advisor`: owns one part of the analysis loop.

## Production extension points

- Replace deterministic signals with live connectors.
- Persist reports in Postgres or SQLite.
- Add auth and organization workspaces.
- Add export hooks for Slack, Discord, Telegram, or email.
