## Look Out the Window (Beginner Project)

This is a small frontend project. You can search short videos by city and time of day and watch them on the page.

### What’s inside
- `index.html` — the page markup
- `styles/` — CSS files (main styles, preloader, errors)
- `scripts/` — JavaScript logic (fetch data, show cards, switch videos)
- `fonts/` — web fonts used on the page

### How to run (the easy way)
Option 1: open `index.html` in your browser (double‑click the file).

Option 2: run a simple local server (recommended):
- If you have Node.js:
```bash
npx serve -s .
```
- If you have Python 3:
```bash
python -m http.server 8080
```
Then open `http://localhost:8080/posmotri-v-okno-fd/` in your browser.

### How to use
1. Type a city (for example: "Санкт Петербург").
2. Choose time of day: Morning / Day / Night.
3. Click the “Найти” button.
4. Click a card in the list to load its video into the big player.
5. If there are more results, click “Показать еще”.

### Where to edit
- Styles: `styles/style.css`
- JavaScript: `scripts/script.js`
- HTML: `index.html`

Tip: If you change class names in HTML, also update selectors in `scripts/script.js` and the CSS.

### Notes
- The design is made to be pixel‑perfect at 1200px width and bigger.
- If something doesn’t load, check your internet and look at the browser DevTools → Network tab.

Good luck and have fun learning! 🎯
