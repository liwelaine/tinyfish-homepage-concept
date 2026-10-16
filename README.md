# TinyFish Homepage Concept — PMM Take-Home

An independent homepage concept for TinyFish, built for the Senior PMM take-home.
It is a single self-contained HTML file. **Not an official TinyFish page and not affiliated with TinyFish.**

- **File:** `index.html`
- **Author:** Elaine (I-Wen Lee)

## How to view

Open `index.html` in any modern browser (double-click it, or drag it into a browser tab), or view the hosted version via GitHub Pages.
Fonts are embedded, so it renders identically offline and when hosted. No build step, no dependencies.

## Deploy (GitHub Pages)

Keep `index.html` and `README.md` at the repository root, then enable Settings → Pages → Deploy from a branch → `main` / `(root)`. The site serves at `https://<username>.github.io/<repo>/`.

Click **PMM notes** in the top ribbon to toggle the inline rationale notes on each section.

## The positioning thesis

The current homepage sells *access* to the web ("the web stack for AI agents"), which is becoming a commodity as competitors converge.
The product and the customers prove something stronger: TinyFish *finishes* multi-step web work in production.
So the concept moves the message from **access → finished work**, and leads with the one thing rivals cannot easily match: TinyFish owns a purpose-built web execution model (Mako) trained on real production data.

## Key decisions

- **Headline:** "Finish the web work other tools can't." Leads with the outcome, not the category. Treated as a claim to validate, not a proven fact (see Evidence discipline).
- **Mako stays out of the hero.** First-time visitors do not know what Mako is, so it is explained in its own section as the technical reason behind the promise.
- **Speaks to both audiences on one page.** A labeled dual entry in the hero (For developers / For enterprise) plus a dedicated "One platform. Two ways in." section, patterned on how Stripe, Cloudflare and Exa route a self-serve motion and a sales-led motion without splitting the positioning.
- **Proof moved up and labeled separately.** DoorDash volume, ClassPass manual-work reduction, and the TinyAgent benchmark measure different things and are labeled as such.
- **Security and data policy surfaced for enterprise.** SSO, audit logs, credential isolation (TinyVault), deployment options, and a clear data-use / model-training policy. This last point is the key enterprise tension: because Mako is trained on production web-task data, the buyer's first question is whether their data trains the model, so the page should answer it directly.
- **Hero example is cross-industry.** The hero demo shows one goal running across a mix of sites (retail, supplier portals, travel, marketplaces, and more) so the page reads as a general platform, not a single vertical. It is labeled illustrative, and a "See real examples" link points to TinyFish's published examples.
- **Breadth, matched to the official site.** A "What you can get done" section covers four cross-industry jobs (Monitor, Enrich, Research, Automate portals), mirroring the strongest part of TinyFish's current homepage but framed around finishing the work and returning structured data.
- **FAQ.** Five questions developers and enterprise buyers actually ask, including a direct data-use and model-training question, which doubles as SEO-friendly content.

## Evidence discipline

TinyFish's culture is evidence over claims, so the concept is careful not to overclaim:

- **"Other tools can't" is a hypothesis to validate,** not a proven head-to-head. It would be backed with task success rate, engineering maintenance hours, and cost per completed workflow before being used as fact.
- **Benchmark vs uptime are separated.** 89.9% on Online-Mind2Web (300 runs public) is TinyAgent's task benchmark; a 99.99% uptime SLA is a separate infrastructure number.
- **Customer numbers are labeled by source** and are not presented as cross-vendor comparisons.
- **No fabricated data.** Interface previews are illustrative concepts, not real customer dashboards, and are labeled as such.

## Links

Real destinations are wired where they exist: Get API Key → `agent.tinyfish.ai`, Talk to Sales → `tinyfish.ai/talk-to-sales`, Docs → `docs.tinyfish.ai`, Trust Center → `trust.tinyfish.ai`. Playground example links point to published TinyFish example pages.

## SEO

The page includes production-grade on-page SEO: descriptive title and meta description, canonical, Open Graph and Twitter Card tags, and JSON-LD structured data (Organization, WebSite, SoftwareApplication) so search and AI answer engines can parse what TinyFish is.

It is intentionally set to **noindex**, because a non-official copy should never compete with the real tinyfish.ai in search. On the real homepage this would be `index,follow` with a self-referential canonical. (A comment in the file marks this.)

## Disclaimer

This is an independent concept for interview purposes only. It is not affiliated with, endorsed by, or an official product of TinyFish. Company names, logos, metrics, and interface previews are used illustratively; publicly reported outcomes are not direct competitor comparisons.
