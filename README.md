# jtrent.dev — Jason Trent (consultant site)

One-page consultant portfolio: architect & engineer for production systems, with a
"work with me" hinge and three clearly-scoped engagement tiers.

## Structure
- `index.html` — the single page (plain HTML, no build step, ~5KB, dark/light aware)

## Hosting
Plain static HTML. Any of: GitHub Pages, Netlify, Cloudflare Pages, or serve from the
VPS. `frontdesk.jtrent.dev` already points at the live frontdesk-intake app, so the
`jtrent.dev` apex domain is available to point here.

## TODO before article launch
- [ ] Swap the `schedule a call` button to a real scheduling link (Cal.com/Calendly)
      once you have one (currently falls back to `mailto:jason@jtrent.dev`).
- [ ] Push to a repo (e.g. `github.com/jason-trentcyber/jtrent.dev`) and wire hosting.
- [ ] Point the domain/apex, or a `www`, at the chosen host.
- [ ] Reference frontdesk-intake with a live link once `frontdesk.jtrent.dev` is pinned
      as the canonical demo URL.