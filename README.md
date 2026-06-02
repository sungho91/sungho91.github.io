# sungho91.github.io

Personal academic homepage of **Sungho Lee** — computational geoscientist, Earthquake Research Center, KIGAM.
The site itself serves as an online CV, split across two pages so the front page stays light.

- 🔗 **Live (after publishing):** https://sungho91.github.io/
- Plain static HTML/CSS — no build step.

## Pages
- [`index.html`](index.html) — **Home (important)**: about, research interests & video highlights, education & appointments, selected publications, contact.
- [`more.html`](more.html) — **Publications, Talks & Activities (details)**: full journal articles, manuscripts in preparation, invited talks, conference presentations, teaching, mentoring, honors, outreach, media.
- [`style.css`](style.css) — shared light academic theme (sticky profile sidebar).

## Media
- `profile.jpg` — profile photo (resized for the web).
- `working_projects/*.mp4` — research animations, embedded as autoplay-loop-muted videos
  (originals were large `.avi`/`.gif`; compressed to small MP4 for fast loading).

## Edit & publish a change
```bash
git add -A
git commit -m "describe change"
git push
```
GitHub Pages rebuilds in ~1 minute.

## To finish
- [ ] Update the **Google Scholar** link in `index.html` / `more.html` (currently a placeholder URL).

## Publish (GitHub Pages — user site)
A repository named exactly `sungho91.github.io` is served at `https://sungho91.github.io/`.
1. Create a public repo named `sungho91.github.io`.
2. Push these files to `main`.
3. Settings → Pages → Deploy from branch → `main` / root → Save.
