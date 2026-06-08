## Hi there 👋

# Manic Millionaire

> **Wealth. Madness. Meaning.**
> Building businesses. Chasing freedom. Trying not to lose my mind in the process.

The personal site of **Ryan De Corsie Ewen** — a domain investor, entrepreneur and adventurer documenting the chaotic pursuit of wealth, freedom and meaning.

Not a guru website. A field journal from someone still figuring it out.

**Live:** [manicmillionaire.com](https://manicmillionaire.com)

---

## About

A single-page personal brand site built around honest, long-form storytelling rather than the usual "millionaire" highlight reel. It covers the full arc — building and selling companies, thousands of domain deals, extreme fitness, burnout, mental resilience and recovery — alongside what's coming next.

### Sections

| # | Section | What's in it |
|---|---------|-------------|
| — | **Hero** | Headline, tagline and primary calls to action |
| — | **Manifesto** | The *Wealth. Madness. Meaning.* statement of intent |
| — | **The Plan** | The long-game goals — IPO, give it away, public life |
| 01 | **My Story** | The honest backstory, wins and breakdowns included |
| 02 | **Topics** | Business · Domains · Fitness · Adventure · Wealth · Mindset |
| 03 | **The Domain Challenge** | Turning $500 into $1,000,000 in one year, documented live |
| 04 | **The Book** | 3D cover mockup + launch details |
| 05 | **Popular Writing** | Featured articles |
| 06 | **Work With Ryan** | Domains, growth, digital assets, mentoring |
| 07 | **Media & Projects** | MillionPlus · DigitalJunkyard · DomainManage |
| — | **Follow** | Social + email update links |

---

## Tech

- **One file.** Everything lives in `index.html` — markup, styles and scripts.
- **No build step, no framework, no dependencies** beyond Google Fonts.
- **Vanilla JS** for the sticky nav, scroll-reveal animations, full-screen mobile menu and the ticker.
- **Type:** Fraunces (display), Hanken Grotesk (body), IBM Plex Mono (labels).
- **Theme:** ink black, bone paper, gold accent — all driven by CSS custom properties at the top of the file, so the whole palette can be re-skinned by editing a handful of variables.

### Run it locally

No tooling required — just open the file:

```bash
open index.html
```

Or serve it (so root-relative links behave like production):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

---

## Deploy (GitHub Pages)

1. Push `index.html` and `CNAME` to a public repo.
2. **Settings → Pages → Deploy from a branch → `main` / root.**
3. DNS — point the apex at GitHub's IPs and `www` at `<username>.github.io`:

   ```
   A     @     185.199.108.153
   A     @     185.199.109.153
   A     @     185.199.110.153
   A     @     185.199.111.153
   CNAME www   <username>.github.io
   ```
4. Enable **Enforce HTTPS** once the certificate is issued.

The included `CNAME` file already sets the custom domain to `manicmillionaire.com`.

---

## To-do before launch

- [ ] Replace placeholder email `hello@manicmillionaire.com`
- [ ] Wire up article links (currently `#`) and project URLs
- [ ] Confirm book title, cover art and launch date (cover is a working mockup)
- [ ] Add favicon and `404.html`

---

## License

© Ryan De Corsie Ewen. All rights reserved.

