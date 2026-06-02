# Small Tools for a Calmer Day

The launcher page for a family of tiny, single-purpose apps — each one fixes a
single modern friction, gently and without shame. Minimal by design: pick one
and open it.

This repo is just the **landing page**. Every app is its own standalone project
that runs on its own, stores everything on your device, and works offline.

## The collection

**Focus & attention** — Lock In · Single-Task · Zola · Linger
**Calm & mind** — Cairn · Brain Dump · Worry Window · Unclench
**Evening & sleep** — Wind Down · One Last Thing · Rise
**Body & health** — Good Bodies · Saleem (سليم) · Water + Up
**Family & connection** — Here · Play With Me
**Habits & restraint** — Essentials · Enough · Sleep On It

## Editing

It's a single static `index.html` — no build step. The card data lives in the
`APPS` object in the inline script; each entry is
`[name, liveURL, icon, description, accent]`. Update a `liveURL` to point a card
at its deployed app.

## Deploy

Static, served from the repo root (see `netlify.toml`). There is no build
command and nothing to install.

## License

MIT.
