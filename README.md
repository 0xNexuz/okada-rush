# Okada Rush

A one-thumb arcade game about riding an okada (motorbike taxi) through Lagos traffic. Pick up passengers at the roadside and drop them at the bus stop that matches their colour before they give up and walk.

**Play:** https://okada-rush.vercel.app

Made for the [Loadout AI Game Competition](https://app.loadout.xyz/jam).

## How to play

- **Steer:** drag anywhere on the screen, or use ← → (A / D).
- **Horn:** tap HORN, or press Space. It clears your lane and scares goats off the road.
- **Pause:** the pause button, or P / Esc.
- Ride along the curb to pick up a waving passenger. Their stop name and colour show at the top left.
- Drop them in the stop zone of the same colour. The faster you drop them, the bigger the tip, and drops in a row build a combo.
- Dodge danfos, cars, kekes, BRT buses and goats. Potholes slow you down. You start with 3 helmets.
- Power-ups: **puff-puff** gives back a helmet, **hot pepper** gives a turbo that smashes through traffic, and the **magnet** pulls in coins.

## Why players come back

- **Garage:** naira you earn is saved. Spend it on upgrades (extra helmet, louder horn, sweet talk, back seat) and six bikes.
- **Daily missions:** three new missions every day at midnight, plus a bonus for finishing all three.
- **Daily Route:** the same road seed for every rider each day. A daily streak pays more each day, and the result can be shared like a Wordle grid.

## Tech

- One self-contained `index.html`: HTML, CSS and vanilla JavaScript on Canvas 2D. No build step and no dependencies.
- Every car, danfo, keke, goat and palm tree is drawn in code. The Afrobeat-style music loop and all sound effects are synthesized with the Web Audio API. `og.png` is only the link-preview image.
- Progress is saved in the browser's `localStorage`.
- Hosted on Vercel as a static site.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
npx serve .
```
