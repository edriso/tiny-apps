# Tiny Apps

The launcher page for a family of tiny, single-purpose apps. Each one does one
thing well and quietly fixes a single modern friction, gently and without
shame. Minimal by design: pick one and open it.

This repo is just the **landing page**. Every app is its own standalone project
that runs on its own, stores everything on your device, and works offline.

## The collection

**Focus & attention:** Lock In · Single-Task · Zola · Linger
**Calm & mind:** Brain Dump · Cairn · Worry Window · Grow & Let Go · Unclench
**Habits & restraint:** Enough · Sleep On It · Essentials
**Evening & sleep:** Wind Down · One Last Thing · Rise
**Body & health:** Water + Up · Good Bodies · Saleem (سليم)
**Family & connection:** Here · Play With Me · I Forgot to Say Sorry
**Faith & gratitude:** Grateful Heart · Munajaa (مناجاة)
**Learning & play:** Number Ninjas · Name It · Type-Down

## Editing

It's a single static `index.html` with no build step. The card data lives in the
`APPS` object in the inline script; each entry is
`[name, liveURL, icon, description, accent]`. Update a `liveURL` to point a card
at its deployed app.

## Deploy

Static, served from the repo root (see `netlify.toml`). There is no build
command and nothing to install.

## License

MIT.
