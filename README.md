# REVEALED

The stories you thought you knew. Mobile-first, no-login Bible and history discovery game for believers, skeptics and curious visitors.

## MVP

Open `index.html` in a browser. Includes 12 playable questions across Bible or Not?, What Happens Next?, and History Detective; sourced explanations; daily challenge; local progress; score tracking; challenge deep links; native share/copy fallback; mobile responsive UI; Awe Faith and AWE Missions links. No build step, API key, cookies, external libraries or backend.

## Hosting

Enable GitHub Pages in repository Settings → Pages → Deploy from branch → main / (root). Published address should then be `https://awemissions.github.io/Revealed/` once GitHub finishes deployment. Confirm Pages is enabled and visit the URL before sharing it.

## Content schema

Each entry in `data` has id, mode, icon, title, q, options, answer (zero-based), detail and source. Every historical claim should distinguish scriptural testimony, independent material evidence, and debated interpretations. Review before publishing new content.

## QA

Test all 12 answers; mode tabs; next loop; daily mystery; deep-link challenge; native share and clipboard fallback; local progress after reload; small Android screens; keyboard and screen reader; reduced-motion; GitHub Pages asset paths.

## Roadmap

1. Add accessible video/illustrated vertical story feed with reviewed content and captions.
2. Introduce curated collections, progress achievements and richer contextual references.
3. Optional privacy-respecting analytics (no device fingerprinting) and an editorial review workflow.
4. Friend competitions with server-side leaderboard only if a backend and abuse controls are warranted.
5. Connect REVEALED to Heath's App Hub after verifying hub repository and deploy workflow.

## Privacy

Progress is stored only in browser localStorage. No server analytics or user accounts in MVP. Sharing is user initiated.
