# BIAB Skincare Website - Technical Architecture

## 1. Technology Stack
- **HTML5**: Semantic markup
- **CSS3**: Modern CSS with variables, flexbox, grid
- **JavaScript**: Vanilla JS for interactivity
- **No Frameworks**: Pure frontend libraries

## 2. File Structure
```
HONEY'S SKIN CO/
├── index.html               # Homepage
├── shop.html              # Product catalog
├── product.html           # Product detail page
├── about.html             # About page
├── contact.html           # Contact page
├── cart.html              # Shopping cart
├── checkout.html          # Checkout page
├── css/
│   └── style.css         # All styles
├── js/
│   ├── main.js
│   └── cart.js
├── images/
│   ├── products/
│   └── brand/
└── .trae/
    └── documents/
```

## 3. Core Modules

### 3.1 HTML Structure
- Semantic tags (<header>, <nav>, <main>, <section>, <footer>
- Accessible ARIA attributes
- Responsive meta tags

### 3.2 CSS Architecture
- CSS custom properties for colors, spacing
- BEM-like naming convention
- Media queries for responsive design
- Flexbox and Grid for layouts

### 3.3 JavaScript Modules
- **Navigation & routing
- Shopping cart state management
- Product filtering & sorting
- Form validation
- Animation triggers

## 4. Data Models

### 4.1 Product Data
```javascript
const products = [
  {
    id: 1,
    name: "BIAB Hydrating Moisturiser",
    price: 45.00,
    description: "...",
    ingredients: ["...", "..."],
    image: "images/products/moisturiser.png"
  },
  // ... more products
];
```

### 4.2 Cart State
```javascript
let cart = {
  items: [],
  total: 0
};
```

## 5. Key Components

### 5.1 Navigation
- Sticky header
- Responsive mobile menu
- Cart counter

### 5.2 Product Cards
- Image
- Title
- Price
- Add-to-cart button
- Hover effects

### 5.3 Cart
- Side drawer or modal
- Quantity controls
- Remove items
- Total calculation

## 6. Styling Guidelines
- Baby pink color scheme
- Soft shadows and rounded corners
- Elegant typography
- Smooth transitions
- Accessible contrast
