# Daksh Jain · Portfolio

Personal portfolio of Daksh Jain, an applied AI and data engineer who thinks in products. The whole site is one page in a single file, with no build step and nothing to install.

**Live:** add your deployed URL here

## What this is

A fast, self contained portfolio that leads with proof. The hero is an interactive 3D teardown, the product work is rebuilt as native graphics rather than screenshots, and the engineering and research are shown with the numbers attached. The visual language is deliberately restrained: a near black canvas, off white type, glass panels, and the only color on the page is live market data.

## Highlights

* **The Unsolvable State.** An interactive Three.js hero. A broken product cube that you can spin, with two corners flagged as faults. Tear it down, patch the technical debt, and watch it reassemble into a clean, fixed core. It degrades gracefully to a short text version when WebGL is unavailable.
* **Glass design system.** Monochrome and material led, in the spirit of a premium product page. Color carries meaning, never decoration.
* **Real product work, shown big.** A Groww screener teardown rebuilt as native graphics (the investor staircase, the five fix audit, the kill gated metrics) and an INDmoney design study with the rationale called out.
* **Engineering and research.** Parley, a realtime chat with semantic memory over a vector database, plus two peer reviewed ML papers.
* **Accessible by default.** Meets WCAG AA contrast, respects the reduced motion preference, and stays fully readable with JavaScript turned off.

## What's inside the page

Engineering, product work, published research, experience, skills, leadership, and contact, in that order.

## Built with

* Plain HTML, CSS, and JavaScript. No framework, no bundler, no dependencies to install.
* Three.js, loaded from a CDN at runtime, for the hero teardown.
* Google Fonts: Schibsted Grotesk for type and JetBrains Mono for labels and the terminal.
* The one image on the page is embedded directly as base64, so `index.html` is fully self contained.

## Project structure

It is intentionally a single file.

```
index.html      the entire site: markup, styles, scripts, and the embedded image
README.md       this file
```

## Run it locally

The simplest way is to open `index.html` in a browser.

To serve it locally so the fonts and Three.js load cleanly:

```
git clone https://github.com/Daksh-22/<repo>.git
cd <repo>
python3 -m http.server 8000
```

Then open `http://localhost:8000`. There is nothing to build and no packages to fetch.

## Deploy

It is a static site, so any static host works. Place `index.html` at the root and point the host at it.

* **GitHub Pages:** push to the repo and enable Pages on the branch.
* **Vercel or Netlify:** import the repo, leave the build command empty, and serve from the root.

The image is embedded, so the file ships on its own. If this URL is already on your job applications, keep it stable when you redeploy.

## Design and accessibility notes

* The page is monochrome by choice. The only chromatic color is market data, green for up and red for down.
* Color is never the only signal. Gains and losses also carry a sign, and the cube faults carry a written label.
* Motion is calm and purposeful, and it scales down for anyone who prefers reduced motion.
* A `noscript` fallback reveals all content and the hero falls back to a short text summary when scripts are disabled.

## Contact

* Email: dakshjain311@gmail.com
* LinkedIn: linkedin.com/in/daksh-jain-3b701322a
* GitHub: github.com/Daksh-22

## Usage

The code is here to read and learn from. The writing, case studies, and personal content are mine, so please do not republish them as your own.

© 2026 Daksh Jain
