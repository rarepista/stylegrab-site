# StyleGrab — marketing site

Static site (`index.html` + `privacy.html`) with a live, working demo of the
StyleGrab inspector (a trimmed port of the real extraction engine). No build
step, no deps.

Live at `https://stylegrab.000426.xyz/`. The `stylegrab` extension repo's
`options/options.html` and `store/listing.md` link to this domain's
`privacy.html` — update those too if the hosting domain ever changes.

## Status

- Contact email and privacy policy: done (`privacy.html`, linked from the footer).
- All "Add to Chrome" CTAs currently point at the extension repo's developer-mode
  install instructions (`github.com/vishalbagi/stylegrab#install-developer-mode`)
  since there's no Chrome Web Store listing yet.

## One TODO before/at CWS launch

Search "TODO" in `index.html` — every CTA has a comment marking where to swap
the GitHub link for the real Chrome Web Store listing URL once the extension is
approved.
