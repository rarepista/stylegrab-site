# StyleGrab — marketing site

Static site (`index.html` + `privacy.html`) with a live, working demo of the
StyleGrab inspector (a trimmed port of the real extraction engine). No build
step, no deps.

Host free on GitHub Pages: Settings → Pages → Deploy from branch → main / root.
Once enabled, the site is live at `https://<your-username>.github.io/stylegrab-site/`
(or a custom domain via a `CNAME` file in this repo, if you configure one).

## Status

- Contact email and privacy policy: done (`privacy.html`, linked from the footer).
- All "Add to Chrome" CTAs currently point at the extension repo's developer-mode
  install instructions (`github.com/vishalbagi/stylegrab#install-developer-mode`)
  since there's no Chrome Web Store listing yet.

## One TODO before/at CWS launch

Search "TODO" in `index.html` — every CTA has a comment marking where to swap
the GitHub link for the real Chrome Web Store listing URL once the extension is
approved. Same swap in `stylegrab/store/listing.md`'s privacy policy URL if you
move this site to a custom domain.
