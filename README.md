# Mera Parichay

**Share your business card, not a link.**

Fill in your details once. The card restyles itself for your profession — then shares straight to WhatsApp, email, or anywhere else, as a photo. Nothing to click, nothing to open.

🔗 **Live:** [https://github.com/AnilThakur007/mera-parichay](https://anilthakur007.github.io/mera-parichay/) <!-- update after enabling GitHub Pages -->

---

## What it does

Mera Parichay is a single-page, no-signup digital business card generator. Type in your details and the card automatically picks a visual style to match your profession — a lawyer's card doesn't look like a chef's, and neither needs a template picked by hand.

### Features

- **Profession-aware styling** — auto-detects your profession from free text and applies a matching design (Advocate, Doctor, Architect, Designer, Real Estate, Teacher, Chef, Fitness Coach, Finance/CA, Engineer, and a general default), each with two style variants to choose from
- **Custom accent color** — override any theme's color with a preset swatch or a full color picker
- **Photo / logo upload** — with automatic background removal (edge-detection based, works best on plain/solid backgrounds), or keep the image exactly as uploaded
- **Watermark** — your own text, single or repeated pattern, adjustable tilt and strength, auto-matched to the active card's font and color
- **3D flip card** — tap to flip and reveal a QR code on the back that saves the contact directly to a phone
- **One-tap actions** — Share (via the native OS share sheet), Save as image, Print (dedicated print layout), Download contact (.vcf)
- **Style randomizer** — a 3D dice button to shuffle through looks
- **Live validation** — inline checks for name, email, phone, and website
- **Fully responsive** — works on mobile and desktop

## Tech stack

Plain HTML, CSS, and JavaScript — no build step, no framework, no backend. Everything runs client-side in the browser.

External libraries (loaded via CDN):
- [html2canvas](https://html2canvas.hertzen.com/) — renders the card to an image for Save/Share
- [qrcode](https://github.com/soldair/node-qrcode) — generates the contact QR code on the card's back

## Running locally

No install needed — it's a single HTML file.

```bash
git clone https://github.com/yourusername/reponame.git
cd reponame
```

Then just open `index.html` in a browser, or serve it locally:

```bash
npx serve .
```

## Deployment

This repo is set up to deploy with **GitHub Pages**:

1. Go to **Settings → Pages**
2. Under "Branch", select the branch this file lives on and `/ (root)`
3. Save — your site will be live at `https://github.com/AnilThakur007/mera-parichay` within a minute or two

## Roadmap

- [ ] More profession styles and style variants
- [ ] AI-based background removal for busier photo backgrounds
- [ ] Hosted profile pages with a shareable link (in addition to the image/QR flow)
- [ ] Team accounts and shared branding

## License

<!-- Choose one and delete the rest, or replace with your own terms -->
All rights reserved © Mera Parichay.

---

<sub>Built with care for people tired of exchanging paper cards — or worse, links.</sub>
