# "BUURG" My Burger Restaurant

A simple static website example for a burger restaurant. It includes pages for the menu (burgers, sides, drinks, desserts), nutritional information, and a simulated shopping cart.

Live demo (GitHub Pages):
- https://anasaemd25.github.io/BUURG-My-Burger-Restaurant/

## Project context

This project is the final assignment for the course “HTML and CSS Programming”. The goal is to design a mobile app UI for a burger restaurant and implement those views as static HTML5 and CSS3 pages without using JavaScript. The assignment emphasizes original design work (no copying existing apps) and proper documentation.

Assignment summary:
- Design a mobile UI for a burger restaurant menu (Burgers, Sides, Beverages, Desserts).
- Include item name, price, image placeholder, description, and a simplified nutritional label (FDA-style examples).
- Provide shopping cart views (list items, quantities, per-item totals, overall total, restaurant selection, navigation back to menu, submit order control).
- Implement responsive layouts using HTML5 + CSS3 only.
- Host the site publicly and submit working links.
- Include a link to the design files (e.g., Figma).

## Project structure

- index.html — Home page
- burgers.html — Burgers menu
- sides.html — Sides menu
- drinks.html — Drinks menu
- desserts.html — Desserts menu
- cart.html — Cart / order interface
- *_nutrition.html — Nutritional information pages (burger-nutrition.html, sides-nutrition.html, drinks-nutrition.html, desserts-nutrition.html)
- imgs/ — Images used by the site

## Technologies and tools

- Technologies: HTML5, CSS3, responsive design with media queries
- Tools: Visual Studio Code, Git, GitHub, GitHub Pages, Figma

## Design and architecture

- Target device: Mobile-first design; pages structured to resemble app views with clear navigation.
- Navigation model:
  - Home: entry point to the four primary menu categories.
  - Category pages: list of items with name, price, image placeholder, description.
  - Nutrition pages: simplified FDA-style labels per category.
  - Cart page: static representation of cart content, quantities, per-item totals, overall total, restaurant selection, and submit order control.
- Page components:
  - Header with back/menu controls and logo.
  - Card-based layout for menu items (image + primary details).
  - Accessibility considerations: `alt` text for images; use of `aria-label` in navigation links.

Note: This is a static prototype with no JavaScript; interactive behaviors are represented visually (e.g., cart and submit controls exist as UI elements, not functional actions).

## How to preview locally

Since this is a static site, you can open `index.html` directly in your browser. For a better local preview (recommended):

Python 3:
```bash
python -m http.server 8000
```

Then open:
http://localhost:8000

Or use any static server (live-server, http-server, etc.).

## Deployment (GitHub Pages)

1. Push the repository to GitHub (already present).
2. In the repository Settings, enable GitHub Pages for the `main` branch and the root (`/`) folder.
3. After a few minutes your site will be available at:
   https://anasaemd25.github.io/BUURG-My-Burger-Restaurant/

## Usage

- Home: Choose a category (Burgers, Sides, Drinks, Desserts).
- Category pages: Browse items (name, price, image placeholder, description).
- Nutrition pages: View simplified nutrition info per category.
- Cart page: See a static preview of how the cart would look, including quantities, per-item totals, overall total, restaurant selection dropdown, and controls to go back to the menu or submit the order (non-functional prototype).

## Submission links

- Live site: https://anasaemd25.github.io/BUURG-My-Burger-Restaurant/
- Repository: https://github.com/anasaemd25/BUURG-My-Burger-Restaurant
- Figma design: https://www.figma.com/design/qW0ZFwcBHa1gi0AwXuiglM/Burger-App?t=TIklEAToeaQEhZlH-1

## Quick customization

- Edit the .html files to change text and content.
- Add or replace images in the `imgs/` folder and update image paths in the HTML files.
- To add global styles, create `css/styles.css` and link it from the HTML files (or modify the existing inline styles).

## Contributing

If you'd like to contribute:
1. Fork the repository.
2. Create a branch: `git checkout -b feature/your-change`
3. Commit and push your changes.
4. Open a Pull Request describing the change.

## Author / Contact

Project by anasaemd25 — https://github.com/anasaemd25
