# "BUURG" My Burger Restaurant

A simple static website example for a burger restaurant. It includes pages for the menu (burgers, sides, drinks, desserts), nutritional information, and a simulated shopping cart.

## Project structure

- index.html — Home page
- burgers.html — Burgers menu
- sides.html — Sides menu
- drinks.html — Drinks menu
- desserts.html — Desserts menu
- cart.html — Cart / order interface
- *_nutrition.html — Nutritional information pages (burger-nutrition.html, sides-nutrition.html, drinks-nutrition.html, desserts-nutrition.html)
- imgs/ — Images used by the site

## How to preview locally

Since this is a static site, you can open `index.html` directly in your browser. For a better local preview (recommended):

Python 3:
```bash
python -m http.server 8000
```

Then open:
http://localhost:8000

Or use any static server (live-server, http-server, etc.).

## Quick customization

- Edit the .html files to change text and content.
- Add or replace images in the `imgs/` folder and update image paths in the HTML files.
- To add global styles, create `css/styles.css` and link it from the HTML files (or modify the existing inline styles).

## Deployment (GitHub Pages)

1. Push the repository to GitHub (already present).
2. In the repository Settings, enable GitHub Pages for the `main` branch and the root (`/`) folder.
3. After a few minutes your site will be available at:
   `https://<your-username>.github.io/Burger-Restaurant/`

## Contributing

If you'd like to contribute:
1. Fork the repository.
2. Create a branch: `git checkout -b feature/your-change`
3. Commit and push your changes.
4. Open a Pull Request describing the change.

Or open an issue to propose improvements or report bugs.

## License

Add a license file if desired (e.g., MIT). Example note:
> License: MIT — see LICENSE (if added)

## Author / Contact

Project by anasaemd25 — https://github.com/anasaemd25
