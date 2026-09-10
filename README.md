# rios-landing

The branded entrance for **remoteinsightos.com** — a pure static landing page
that routes visitors to the three RIOS "doors":

| Door | Destination (placeholder until DNS is wired) |
|---|---|
| **Admin** | `https://app.remoteinsightos.com` |
| **VA** | `https://va.remoteinsightos.com` |
| **Client** | `https://client.remoteinsightos.com` — **disabled / "Coming soon"** |

No backend, no auth, no data, no functions — just `index.html` and three links.

## Deploy (held — not wired yet)
Deploy as the **apex** Netlify site (`publish = "."`). The door targets are
**placeholders**; the real subdomains don't exist yet — see the domain-routing
plan. Point `remoteinsightos.com` here **after** the admin dashboard is moved
off the apex to `app.remoteinsightos.com` (otherwise this page overtakes the
live admin dashboard).

## Brand
Warm-dark RIOS tokens (`#1B1714` ground, `#58A6FF` accent, `#F7F0E8` text),
Sora + IBM Plex Mono — consistent with the gate/dashboard. The ambient
"signal field" is a decorative canvas radar; it degrades to a static image
under `prefers-reduced-motion`.
