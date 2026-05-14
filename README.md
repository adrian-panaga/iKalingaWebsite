# iKalingaSMS — Website

The official website for **iKalingaSMS**, an offline desktop SMS messaging app built for nursing students at the City Camp District Health Center, Baguio City, Philippines.

🌐 **Live site:** https://adrian-panaga.github.io/iKalingaWebsite/

---

## What this repo is

This repo contains the source for the iKalingaSMS product website, hosted on GitHub Pages. It is a single-page static site (`index.html`) — no build tools, no frameworks, no dependencies.

The site covers:
- What iKalingaSMS is and why it was built
- Download link (Google Drive)
- Installation and setup instructions
- Release notes and version history
- Community bug report and feature request forms
- Privacy and RA 10173 compliance information
- FAQ

---

## Repo structure

```
iKalingaWebsite/
├── index.html          # The entire website (HTML + CSS + JS, single file)
├── assets/
│   └── iKalingaSMS-Logo.png
└── README.md
```

---

## How to update the site

All edits are made directly to `index.html`. After saving, push to GitHub and the live site updates automatically within a minute or two.

```bash
git add index.html
git commit -m "Your description here"
git push
```

### When a new app version is released

Two places need updating in `index.html`:

1. **Download section** (search for `dl-title`) — update the version number and release date, and replace the Google Drive link if the installer changed.

2. **Release Notes section** (search for `release-notes`) — add a new `<div class="rn-card">` block at the top describing what changed in the new version.

That's it. Push, and the site reflects the new release.

---

## Local development

No setup required. Just open `index.html` in a browser:

```
C:\Adrian\iKalingaWebsite\index.html
```

> **Note:** JavaScript runs correctly when opened locally. The FAQ and Release Notes accordions, smooth scrolling, and mobile nav all work without a local server.

---

## Related

- **Bug reports:** https://forms.gle/AFVFBJJEGbjb2Fc38
- **Feature requests:** https://forms.gle/9kFkyohzcz4pxE9f7

---

## License

This website and the iKalingaSMS application are free for use by community health centers. Built as a quality improvement initiative by SONAHBS Nursing Students, Baguio City, Philippines.
