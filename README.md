# FORMA — Mannequin Atelier & Clothing Studio

A one-page interactive fashion atelier, built as a study project and hosted free on Render.

**Open the live website: https://forma-v3.onrender.com**

> First visit can take 30-60 seconds to load. The site runs on a free hosting plan that sleeps when nobody is visiting, then wakes up on your first click.

## What the site is

FORMA is a single continuous page that opens like a story:

1. **Build your own look** — a 3D fitting room. Pick a collection (Her or His), tap tops, layers, bottoms, dresses, shoes and accessories, and watch each piece dress a rotatable 3D form. Your look has a live total and can be added to the bag in one tap.
2. **The 3D Atelier** — a live cloth simulation. A stylized tailor's form wears real simulated cloth (~600 particles): drag the fabric, raise the wind, throw a gust, and swap between linen, silk and wool to feel the different weights.
3. **The Scanned Studio** — photoreal scanned models you can spin a full 360 degrees. Choose Her or His, then jump between complete scanned looks.
4. **The Shop** — a 28-piece collection with search, filters, sorting, a server-side bag and a demo checkout.

## Screenshots

![Opening page — FORMA hero](https://github.com/user-attachments/assets/770d94ed-03ae-4d75-8294-2da27f436b74)

![Build your own look — 3D fitting room](https://github.com/user-attachments/assets/615c91de-6eec-49f0-88d9-5e913484da5c)

![3D Atelier — live cloth simulation](https://github.com/user-attachments/assets/e0251086-225a-41ce-9cd7-fdaee3bfeeba)

![Scanned Studio — photoreal 360 models](https://github.com/user-attachments/assets/71a80cb9-4e52-4891-8a3b-8177573b68b9)

![The collection — shop every piece](https://github.com/user-attachments/assets/4641f467-b67d-4f8c-b524-a46741f31942)

## Tech

- Node.js + Express server, plain HTML/CSS/JS front end, no build step.
- Three.js for the fitting room, the cloth simulation and the scanned studio.
- Garment meshes are CC0 assets from CharacterCreator/MakeHuman output; the upstream program code is not used.
- Bag and orders are stored server-side as JSON files.

## Honest demo notes

- This is a learning/demo project, not a real store. Prices, stock, shipping and checkout are fictional; checkout only records a demo order, with no payments or fulfillment.
- Free hosting means the shared demo bag and orders reset whenever the instance restarts or redeploys.
- Made as a study project. Feedback is welcome.
