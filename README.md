# FurniNest

A responsive furniture storefront demo built with HTML, CSS and vanilla JavaScript.

## Preview locally

Open `index.html` in a browser. The site has no build step or package dependencies.

## Included interactions

- Browse furniture by category and search or sort the sample catalog.
- Save products to a browser-based wishlist.
- Add products to a cart and update quantities.
- Run a simulated checkout and view a sample order status.

The checkout is a frontend demo. It does not request personal details, process payments, send orders, or connect to a backend. Cart, wishlist and sample order state are stored in the browser's local storage.

## Deploy with GitHub Pages

The workflow in `.github/workflows/deploy.yml` publishes the repository root to GitHub Pages whenever a commit is pushed to `main`.
