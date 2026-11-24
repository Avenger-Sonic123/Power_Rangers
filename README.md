# Power Rangers Canvas

A keyboard-controlled image composition exercise.

**Repository created:** 2021-08-06  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2021-08-06

## Features and implementation

- Fabric.js canvas.
- Color-specific character sprites.
- Key events for R, G, Y, P and B.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery, Fabric.js.

## How the code works

`my_keydown()` handles keyboard events and `new_image()` adds the selected character image to the canvas.

## Project structure

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |
| [`style.css`](style.css) | Page styling |

Key functions in the source:
- `main.js`: `new_image()`, `my_keydown()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/Power_Rangers.git
cd Power_Rangers
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Press R, G, Y, P or B to add character images to the canvas.

## Current status and limitations

This is an image placement exercise, not a combat game.

---

Source reference: [`de995cd8`](https://github.com/Avenger-Sonic123/Power_Rangers/tree/de995cd85be83964851d24ee2cf4624581e784ae) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
