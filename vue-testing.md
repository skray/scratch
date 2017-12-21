## Why testing

Quick example of the tedium of manually testing deep in the guts of a web app - example: e-commerce (everyone builds their own e-commerce site right)

## Basics - intro to Jest

Start with simple tests for ... dollerize.js

- Add dollar sign to number
- Now need to add decimals, run into null pointer issues
- Add commas, handle negatives and non-numeric values, etc.

## Testing vue - back to e-commerce site

Use dollarize in my super cool ecommerce website

- Show list of items (test comp initialization, basic DOM checking)
- Load list from API (asynchronous testing)
- Filter list (form input testing)
