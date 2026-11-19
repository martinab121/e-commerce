# E-Commerce Application (React starter)

A React + Vite starter for a small e-commerce page with a product list and a shopping cart. The components and layout are in place, but the product rendering and cart logic are not implemented yet.

## What is in place

- `App.jsx` renders an "E-Commerce Application" heading with a `ProductList` and a `ShoppingCart` component
- `ProductList` defines three sample products (name and price) and a styled, currently empty list
- `ShoppingCart` renders a styled, currently empty cart list and a "Clear Cart" button
- Redux Toolkit and React Redux are installed, and `CartSlice.jsx` exists as an empty stub (no store is configured yet)

## Tech stack

| Area | Technology |
| --- | --- |
| UI | React 18 |
| State management | Redux Toolkit, React Redux (installed, not yet wired up) |
| Build tool / dev server | Vite 5 |
| Linting | ESLint (react, react-hooks, react-refresh plugins) |

## Project structure

```
src/
├── App.jsx
├── main.jsx
└── Components/
    ├── ProductList.jsx   # Product list with sample data
    ├── ShoppingCart.jsx  # Cart layout and Clear Cart button
    └── CartSlice.jsx     # Redux slice (stub)
```

## Getting started

Requires Node.js and npm.

```bash
npm install
npm run dev
```

Then open the local URL printed by Vite. Other scripts: `npm run build`, `npm run lint`.

---

Learning project based on IBM Skills Network starter code (Apache 2.0, see `LICENSE`).
