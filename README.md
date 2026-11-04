# Which Council?

A guessing game: name the UK local authority from its logo, with the place name blacked out.

**[Play it here](https://maxlangerml-collab.github.io/council-logo-game/)**

## How to play

- **Easy** – pick the right council from four options (keys 1–4 work too).
- **Hard** – type the name and choose from the autocomplete.
- **Time trial** – type as many as you can before the clock runs out (60 seconds by default, or choose your own time).
- Filter by region (England, Scotland, Wales or Northern Ireland), or play with all of the UK.
- Filter by tier: **upper tier** is county councils plus every single-tier council (unitaries, metropolitan and London boroughs, and all councils in Scotland, Wales and Northern Ireland); **lower tier** is England's district councils.
- Easy and Hard rounds are 10 logos. The full logo is revealed after every answer.

## On a touchscreen stand

Open the game with `?kiosk` on the end of the address:

https://maxlangerml-collab.github.io/council-logo-game/?kiosk

Kiosk mode is one fixed game: a 60-second time trial on the 153 upper-tier councils in England, picking the answer from four options, with the settings hidden and a "best on this stand" score. It starts on a "Touch to play" screen and goes back to it after 60 seconds without a touch, abandoning any unfinished round (a running time trial is never cut short). To change the wait, add the number of seconds, for example `?kiosk=90`. Kiosk mode also turns off text selection and long-press menus. For a true full-screen stand, run the browser in kiosk mode (for example, Chrome or Edge with `--kiosk`) or press F11.

## What's in here

- `index.html` – the whole game; no build step or server needed.
- `data.json` / `data.js` – the list of councils (`data.js` lets the page work when opened straight from disk).
- `img/` – logos with the name redacted, shown while guessing.
- `reveal/` – the original logos, shown after answering.

381 current UK councils are included. Image file names are random so they don't give away the answer.

## Credits

Logos are the property of their respective councils and are used here for a non-commercial quiz. Most were sourced from Wikipedia; a few came from the councils' own websites. Council list from [mySociety](https://github.com/mysociety/uk_local_authority_names_and_codes).
