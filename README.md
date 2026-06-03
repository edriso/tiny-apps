# Tiny Apps

The home for a family of tiny, single-purpose apps. Each one does one
thing well and quietly fixes a single modern friction, gently and without
shame. Minimal by design: pick one and open it.

This repo is just the **landing page**. Every app is its own standalone project
that runs on its own, keeps everything on your device, and works offline.

## The collection

The apps are sorted into simple themes, like focus, calm, sleep, body, family,
faith, learning, and dev reference. The page itself is the source of truth, so
open the live site (or `index.html`) to see the full, up-to-date list.

## Editing

It is a single static `index.html` with no build step. All the cards live in the
`APPS` object in the inline script, grouped by category. Each entry is
`[name, liveURL, icon, description, accent]`.

To add an app, drop a new entry into the right group. To add a whole new group,
add a key to `APPS` and a matching `<div class="grid" id="g-yourkey">` in the
page. To point a card at its live site, change its `liveURL`.

## Deploy

A static site served straight from the repo root. There is no build step,
nothing to install, and no config needed. It works on any static host, such as
GitHub Pages, Netlify, or Vercel.

## License

MIT.
