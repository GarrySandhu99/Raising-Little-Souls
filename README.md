# Raising Little Souls

Static website (HTML + CSS only). No JavaScript, Node, React, or Next.js.

## How to view

- **Option 1:** Double-click `index.html` to open in your browser.
- **Option 2:** Run a local server:
  ```bash
  python3 -m http.server 8080
  ```
  Then open http://localhost:8080

## What's here

+ `index.html` — Home (VLOGS list)
+ `about.html` — About
+ `contact.html` — Contact
+ `category/` — Sleep, Nutrition, Baby Activities, Product Picks
+ `posts/` — Individual post pages
- `styles.css` — All styling (colours, layout, fonts)

## Adding a new post

1. Create a new `.html` file in `posts/` (copy an existing one and change the content).
2. Add a card for it on `index.html` in the VLOGS grid.
3. Add a card on the right `category/xxx.html` page.

You can host this on any host that serves static files (no server or build step needed).
