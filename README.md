# Shashidhar Patil — Portfolio

**Live site:** https://shashidharpatil96.github.io

The personal portfolio of Shashidhar Patil, a senior full-stack engineer in Bangalore who builds crew scheduling and flight operations software at Delta Air Lines.

The site tells my career as a single flight. As you scroll, a cel-shaded 3D jet flies through a dusk sky past a floating island for each company I've worked at. Each island shows that company's domain.

| Years | Company | Domain | Island shows |
|---|---|---|---|
| 2018 – 2019 | Victorious IT Solutions | On-demand errands | A shop, a courier and a customer's home |
| 2019 – 2023 | MSG Global Solutions | Health & auto insurance | A hospital, health cover and an insured car |
| 2023 – 2024 | Virtusa (client: JPMorgan Chase) | Banking | A bank, transactions and controls |
| 2024 – now | Delta Air Lines | Airline operations | Ops control, crew and flights |

## Sections

- **Story:** a scroll-driven 3D intro, the career flight plan, and the crew-app monitoring flow (detect, alert, auto rollback, root cause)
- **About:** photo, bio and quick facts
- **Selected work:** crew operations platform, self-healing monitoring, driver scoring engine, health registration PWA, an Angular 6 → 15 upgrade, and **Triova**, my personal India-first travel super app (in progress)
- **How I build with AI:** how I use AI day to day to understand code, scaffold, test, triage incidents, ship, and build side projects, plus my ground rules for using it safely
- **Toolkit:** languages, frameworks, cloud, messaging and DevOps tools, plus certification and education
- **Contact:** email, LinkedIn and GitHub

## Built with

- A single self-contained `index.html` with HTML, CSS and JavaScript, and no build step
- [three.js](https://threejs.org/) 0.160 for the 3D scene, loaded from jsDelivr, with toon materials and ink outlines
- The [Instrument Sans](https://fonts.google.com/specimen/Instrument+Sans) font from Google Fonts
- Hosted on GitHub Pages

It works on phones, follows the reduced-motion setting, and still shows all its content if WebGL isn't available.

## Run locally

```bash
git clone https://github.com/Shashidharpatil96/Shashidharpatil96.github.io.git
cd Shashidharpatil96.github.io
python3 -m http.server 8000
# open http://localhost:8000
```

You need an internet connection, because three.js and the font load from CDNs.

## Updating

Edit `index.html` and push to `main`. GitHub Pages redeploys automatically within a minute or two.

## Contact

- Email: shashidhar.star50@gmail.com
- LinkedIn: [shashidhar-patil-33701b131](https://www.linkedin.com/in/shashidhar-patil-33701b131/)
- GitHub: [Shashidharpatil96](https://github.com/Shashidharpatil96)
