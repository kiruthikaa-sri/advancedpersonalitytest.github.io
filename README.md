# Ms Mantissa

An unlicensed fortune-teller who reads your personality and mildly insults you about it.

**[Live demo →](https://kiruthikaa-sri.github.io/advancedpersonalitytest.github.io/)**

Ms Mantissa is a single-page, no-build personality quiz with a carnival fortune-teller aesthetic. Answer five questions, watch her "consult the spirits," and receive a reading you didn't ask for but definitely deserve.

## Features

- **In-character intro screen** with a disclaimer that doubles as a joke
- **Five-question quiz flow** with a gold-on-wine carnival cabinet design
- **Fake diagnostic scan** a spinning crystal-ball animation and status lines before your result appears
- **Randomized roast results** so repeat visits get a different verdict
- **Custom cursor** a glowing ring-and-dot cursor with a soft pink trail that follows your mouse
- **Fully responsive**, keyboard-accessible, and respects `prefers-reduced-motion`
- **Zero dependencies** just HTML, CSS, and  JS in a single file

## Getting started

No build step, no installation. Just open terminal in your system and paste these codes:

```bash
git clone https://github.com/kiruthikaa-sri/advancedpersonalitytest.github.io.git
cd advancedpersonalitytest.github.io
start index.html   # or double-click the file
```
*P.S: Click Enter after pasting the code*
Or serve it locally:

```bash
python -m http.server
```
Or
```bash
python3 -m http.server
```
then visit `http://localhost:8000/`.

## Customizing

Everything lives in one file, so it's easy to make it your own:

| To change... | Edit... |
|---|---|
| Questions and answers | the `questions` and `answers` arrays |
| Roast results | the `roasts` array |
| Colors and theme | the CSS custom properties in `:root` |
| Cursor style | the `cursor` rules on `html, body` and `button` |

## Tech stack

- HTML
- CSS (custom properties, animations, no frameworks)
-  JavaScript (no libraries)

## License

MIT — do whatever you want with it.
