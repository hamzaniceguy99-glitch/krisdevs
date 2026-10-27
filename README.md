# KRISDEVS — software & it consultancy

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `krisdevs.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/krisdevs.mjs`).
> To change the content, edit that file and run `node build.mjs krisdevs` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@krisdevs.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are KRISDEVS, a software development and IT consultancy based in Genk, Limburg. We build custom software, integrate and automate systems that do not talk to each other, give technical second opinions on code and suppliers before a client commits money to either, and set up the documentation and handover that lets someone else take over. We are a one-person company and we say so plainly, because that is a single point of failure and a client deserves to weigh it: documentation is delivered as work proceeds, every account and domain is held in the client's own name, source code can be deposited with a third party, and a named successor is agreed for longer engagements. We also structure engagements so they are not at risk of being reclassified as employment, which is a liability that falls on the client as well as on us. Site: krisdevs.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
