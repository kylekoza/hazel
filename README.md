# 🦋 Hazel's Rainbow Flutter

A cheerful little browser game made for Hazel, who loves rainbows and butterflies.

You're a butterfly fluttering through a pastel sky. Catch the **little rainbows** to grow
your wings, dodge the **grumpy storm clouds** (and any rainbow bigger than you), and fill
the whole sky with color to clear each level.

**▶️ Play it: [www.kylekoza.com/hazel](http://www.kylekoza.com/hazel/)**

## How to play

- **Fly** with your **mouse**, or the **arrow keys / WASD**. On a touchscreen, just drag your finger.
- **Sparkle dash** with **Space** or a **click/tap** for a quick burst of speed (it recharges after a moment).
- **Pause** with **P**.
- Catch rainbows **smaller than you** to grow. Chain catches quickly to build a **combo** for bonus points.
- Steer clear of anything **bigger** than you — storm clouds chase you, and big rainbows will bump you.
- Grow big enough to fill the sky and you clear the level. Then you fly higher into a faster one!

## Difficulty

Pick a tier on the start screen — your choice is remembered, and best scores are tracked
separately for each.

| Tier | Who it's for | Feel |
| --- | --- | --- |
| 🌸 **Easy** | Little ones (this is Hazel's) | Slow critters, hardly any storm clouds, fast growth, a long safe start, and only *much*-bigger things can bump you. |
| 🦋 **Normal** | A friendly challenge | A few storm clouds to dodge and a steadier pace. |
| ⛈️ **Hard** | Big kids | Fast rainbows, lots of grumpy clouds, and slower growth. |

## Running it locally

It's a single, self-contained HTML file — no build step, no dependencies, no server required.
Just open `index.html` in any modern browser (double-click it, or drag it into a browser window).

## Tech

Plain HTML, CSS, and vanilla JavaScript rendering to a `<canvas>`. Sound effects are generated
on the fly with the Web Audio API, and best scores are saved in `localStorage`. Everything lives
in [`index.html`](index.html).

## Deployment

Hosted on GitHub Pages from the `master` branch, served at
[www.kylekoza.com/hazel](http://www.kylekoza.com/hazel/). Pushing to `master` redeploys automatically.
