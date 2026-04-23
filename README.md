# Paradise Nursery 🌿

A React-based e-commerce shopping application for houseplants built with Redux Toolkit for state management.

## Project Overview

Paradise Nursery is a front-end shopping application that allows users to browse a variety of houseplants, add them to a shopping cart, and manage their purchases before checkout.

## Features

- **Landing Page**: Beautiful background image with company name, tagline, and "Get Started" button
- **Product Listing Page**: Browse 5 categories of houseplants (30+ plants total) with thumbnails, names, and prices
- **Shopping Cart**: View all selected items, adjust quantities, remove items, and see total cost
- **Redux State Management**: Cart state managed globally using Redux Toolkit

## Tech Stack

- React 18
- Redux Toolkit
- Vite
- CSS3

## Project Structure

```
e-plantShopping/
├── src/
│   ├── App.jsx          # Landing page with background image and Get Started button
│   ├── App.css          # Landing page styles including background image
│   ├── AboutUs.jsx      # Company information component
│   ├── AboutUs.css      # About Us styles
│   ├── ProductList.jsx  # Product listing page with navbar and plant categories
│   ├── ProductList.css  # Product listing styles
│   ├── CartItem.jsx     # Shopping cart page component
│   ├── CartItem.css     # Shopping cart styles
│   ├── CartSlice.jsx    # Redux slice for cart state management
│   ├── store.js         # Redux store configuration
│   ├── main.jsx         # App entry point with Redux Provider
│   └── index.css        # Global styles
├── index.html
├── package.json
└── vite.config.js
```

## Plant Categories

1. **Air Purifying Plants** – Snake Plant, Spider Plant, Peace Lily, Boston Fern, Rubber Plant, Aloe Vera
2. **Aromatic Fragrant Plants** – Lavender, Jasmine, Rosemary, Mint, Lemon Balm, Hyacinth
3. **Insect Repellent Plants** – Oregano, Marigold, Geraniums, Basil, Citronella, Catnip
4. **Medicinal Plants** – Echinacea, Peppermint, Chamomile, Calendula, Turmeric, Ginger
5. **Low Maintenance Plants** – ZZ Plant, Pothos, Cast Iron Plant, Succulents, Aglaonema, Dracaena

## Getting Started

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build
```

## Deployment

This app is deployed using GitHub Pages.

## License

MIT