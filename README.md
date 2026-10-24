# Calculatorfun

A playful math game for kids (ages 4 to 99). Mira the little witch brews numbers in her cauldron.

## How to play

1. Throw a **number bubble** into the cauldron.
2. Throw a **second number bubble**.
3. Throw a **potion bottle**: plus (+), minus (−), times (×) or divided by (÷).
4. Mira stirs, the cauldron bubbles, and she spits out the **result** as a golden bubble.

You can drag and fling bubbles, or simply tap one and it flies into the cauldron by itself.
The golden result bubble can be thrown back in as a new number.

On a keyboard: `1`–`9`, `0` for 10, and `+` `-` `*` `/` for the potions.

## Runs everywhere

Phones, tablets and laptops, in portrait and landscape. Mouse, touch and keyboard all work.

## Tech

- A single `index.html` file: HTML, CSS and JavaScript, no build step
- Physics: [Matter.js](https://brm.io/matter-js/) 0.19.0, loaded from cdnjs
- Graphics: drawn on an HTML canvas (the witch and all game art are original drawings in code)
- Sounds: generated live with the Web Audio API

## Try it locally

Download `index.html` and open it in a browser. That's it.

## Publish with GitHub Pages

The repository must be public on the free GitHub plan.

1. Settings → Pages
2. Source: **Deploy from a branch**, Branch: **main**, Folder: **/ (root)** → Save
3. After a minute or two the game is live at `https://aniko-creator.github.io/calculatorfun/`

## License

MIT, see [LICENSE](LICENSE).
