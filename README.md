# Product Catalog (React)

This project demonstrates React component composition and props usage.

## Components

Navbar
Displays the application title and total number of products.

ProductCard
Displays product information including name, price, category, and image. Featured products have a gold border.

CardWrapper
A reusable layout wrapper that adds consistent styling using the children prop.

ProductGrid
Uses .map() to render a list of ProductCard components.

## Data
Product data is stored in products.js for better separation of concerns.

## Features
- Dynamic rendering using .map()
- Props destructuring
- Conditional styling
- Component composition