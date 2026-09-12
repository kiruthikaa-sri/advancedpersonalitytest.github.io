# Ms Mantissa

Meet Ms Mantissa, a fortune-teller with questionable qualifications who takes one look at your personality and isn't afraid to say what she thinks. She brings a carnival fortune-telling experience to life. Answer five questions, let Ms Mantissa consult the spirits and prepare yourself for a reading that might be a little too accurate.

**[Live demo(click here to open website) ](https://kiruthikaa-sri.github.io/advancedpersonalitytest.github.io/)**

## Features

- **In character intro screen** with a disclaimer that also works as a joke
- **Five-question quiz sequence** with a gold-on-wine carnival cabinet theme
- **Bogus diagnostic scan** a spinning crystal ball animation and status messages before your results are revealed
- **Randomized roasts** so that you don’t see the same message each time
- **Special cursor** an animated glowing ring and dot cursor with a pink trail
- **Responsive, accessible, and motion preferred** zero dependencies with just HTML, CSS, and JS in one file

## Getting started

No build step, no installation. Just open terminal in your system and paste these codes:

```bash
git clone https://github.com/kiruthikaa-sri/advancedpersonalitytest.github.io.git
cd advancedpersonalitytest.github.io
start index.html   # or double-click the file
```
*Or serve it locally:*

```bash
python -m http.server
```
or
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

MIT License : do whatever you want with it.
