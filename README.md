# awacs-hull

The Pragma Digital fleet's first **cloud-hulled agent** — deployed to Cursor-managed hosting
under the sterile-hull pattern (RULING-TRIPPE-GROK-AGENT-SDK-REPO-20261028, Law H-2/29 by
construction). Off-station burn: every orbit fires on Cursor's infrastructure, never ours.

## What it does

Hourly radar sweep of the vendor release horizon (Bun · opencode · Cursor · Claude Code ·
Tailscale · xAI). Deltas only. The report lands in each orbit's session transcript.

## Membrane

This repo is STERILE BY DESIGN: agent scaffold + instructions only. No fleet code, no client
code, no `.trix/` tokens, no keys, no estate paths. If a change needs any of that, the change
is wrong.

## Reading the radar

```bash
agent-sdk session list --dir .   # hosted sessions
agent-sdk logs --once --dir .    # last logs
```

## Redeploy

```bash
agent-sdk validate --dir .
agent-sdk deploy --dir .         # repo/ref inferred from origin
```

*Hull home: `~/Code/hulls/awacs-hull` (olympic) · Org: Holistic-Dogma · Minted: Crown
Scale-Out session, 2026-10-29.*
