# Felix Dukes — Portfolio Site

A single-page portfolio site for a technical & UX writer. Self-contained static HTML — no build step, no dependencies.

## Files

- `index.html` — the entire site (markup, styles, and script in one file)

## Editing content

Everything is placeholder text ready to be swapped for the real thing:

- **Work samples** — the four cards under `id="work"`. Replace the title, description, tags, and `View case study →` links with your own case studies (or link out to hosted docs/PDFs).
- **Résumé link** — the "Résumé (PDF)" button in the contact section currently points to `#`. Update the `href` once you have a resume file hosted somewhere.
- **About section** — the two paragraphs and the fact list (`Focus`, `Tools`, `Based in`, `Currently`) under `id="about"`.
- **Capabilities** — the four rows under `id="capabilities"`, if your focus areas differ.

Name, email, and LinkedIn are already filled in.

## Previewing locally

Just open `index.html` directly in a browser — double-click it, or run:

```bash
open index.html      # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

## Hosting

Any static host works since there's no backend or build process. A few easy options:

- **GitHub Pages** — push this file to a repo, enable Pages in repo settings, point it at the branch/root.
- **Netlify / Vercel** — drag-and-drop the folder onto their dashboard, or connect a GitHub repo for auto-deploys.
- **Any web host** — upload `index.html` to the server's public/root directory.

## Notes

- Built with system-safe fallback fonts (serif/sans/mono) — no external font files required.
- Responsive down to mobile; respects `prefers-reduced-motion` for the hero animation.
