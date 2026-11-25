# Materials & Orders Manager

A simple single-page web app for managing materials inventory and customer orders.

## Features

- **Add materials** — name, quantity, and unit price
- **View materials list** — shows stock and total value
- **Create orders** — select a material, quantity, and customer name
- **Stock validation** — prevents ordering more than available quantity
- **Cancel orders** — restores stock when an order is cancelled
- **Persistent storage** — all data is saved in the browser’s `localStorage`

## How to run

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari).
2. No server or installation required — it works offline.

## Data storage

Data is stored under these keys in `localStorage`:

| Key                      | Content              |
|--------------------------|----------------------|
| `materials_app_materials`| Array of materials   |
| `materials_app_orders`   | Array of orders      |

Clearing browser data or using private/incognito mode will reset the app.

## File structure

```
.
├── index.html      # The complete web app (HTML + CSS + JS)
├── README.md       # This file
└── prompt_log.md   # Log of the prompts used to build this project
```

## Browser support

Works in all modern browsers that support:

- `localStorage`
- ES6+ JavaScript
- CSS custom properties

## License

Free to use and modify for any purpose.
