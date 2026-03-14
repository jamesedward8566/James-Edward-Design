# PhoneVault - iPhone & Samsung E-Commerce Site

## 1. Project Overview

- **Project Name**: PhoneVault
- **Type**: E-commerce landing page (single-page website)
- **Core Functionality**: Display and sell iPhones and Samsung devices with pricing, brand filtering, and shopping cart functionality
- **Target Users**: Customers looking to purchase premium smartphones

## 2. UI/UX Specification

### Layout Structure

**Header**
- Fixed navigation bar at top
- Logo (left): "PhoneVault" with phone icon
- Navigation links (center): Home, iPhones, Samsung, Deals
- Cart icon with item count badge (right)

**Hero Section**
- Full-width hero with featured promotion
- Headline: "Premium Smartphones, Unbeatable Prices"
- Subheadline: "Shop the latest iPhone and Samsung devices"
- CTA button: "Shop Now"

**Filter Bar**
- Brand filter buttons: All | Apple | Samsung
- Sort dropdown: Featured | Price: Low to High | Price: High to Low

**Product Grid**
- 3 columns on desktop, 2 on tablet, 1 on mobile
- Product cards with image, name, specs summary, price, "Add to Cart" button

**Footer**
- Contact info, social links, copyright

### Visual Design

**Color Palette**
- Primary: `#0a0a0a` (deep black)
- Secondary: `#1a1a1a` (card backgrounds)
- Accent: `#0071e3` (Apple blue)
- Samsung accent: `#1428a0` (Samsung blue)
- Success: `#34c759` (green for cart)
- Text primary: `#ffffff`
- Text secondary: `#8e8e93`
- Border: `#2c2c2e`

**Typography**
- Headings: "SF Pro Display", -apple-system, sans-serif
- Body: "SF Pro Text", -apple-system, sans-serif
- Logo: 24px bold
- H1: 48px bold (hero)
- H2: 32px semibold (section titles)
- Product name: 18px semibold
- Price: 24px bold
- Body: 16px regular

**Spacing System**
- Section padding: 80px vertical
- Card padding: 24px
- Grid gap: 24px
- Container max-width: 1200px

**Visual Effects**
- Card hover: translateY(-8px), box-shadow increase
- Button hover: brightness increase, scale(1.02)
- Smooth transitions: 0.3s ease
- Gradient overlay on hero

### Components

**Product Card**
- Device image (200x200 container)
- Brand badge (Apple/Samsung)
- Product name
- Key specs (storage, display)
- Price
- "Add to Cart" button
- Hover state: lift effect

**Cart Sidebar**
- Slide-in from right
- Product list with quantity controls
- Total price
- "Checkout" button
- Empty cart state

**Filter Buttons**
- Pill-shaped buttons
- Active state with accent color
- Hover: background lighten

## 3. Functionality Specification

### Core Features

1. **Product Display**
   - Show 6 iPhone models with prices
   - Show 6 Samsung models with prices
   - Display product image, name, storage option, price

2. **Brand Filtering**
   - "All" shows all products
   - "Apple" filters to iPhones only
   - "Samsung" filters to Samsung only
   - Smooth fade animation on filter

3. **Price Sorting**
   - Featured (default order)
   - Price: Low to High
   - Price: High to Low

4. **Shopping Cart**
   - Add products to cart
   - Update quantities (+/-)
   - Remove items
   - Calculate total
   - Cart badge shows item count
   - Persist cart in localStorage

5. **Responsive Design**
   - Mobile: 1 column grid
   - Tablet: 2 column grid
   - Desktop: 3 column grid

### Products Data

**iPhones**
1. iPhone 16 Pro Max - $1,199 (256GB)
2. iPhone 16 Pro - $999 (256GB)
3. iPhone 16 - $799 (128GB)
4. iPhone 15 Pro Max - $999 (256GB)
5. iPhone 15 Pro - $799 (128GB)
6. iPhone 15 - $699 (128GB)

**Samsung**
1. Galaxy S25 Ultra - $1,299 (256GB)
2. Galaxy S25+ - $999 (256GB)
3. Galaxy S25 - $799 (128GB)
4. Galaxy Z Fold 6 - $1,799 (256GB)
5. Galaxy Z Flip 6 - $999 (256GB)
6. Galaxy S24 Ultra - $1,299 (256GB)

## 4. Acceptance Criteria

- [ ] Header displays logo, navigation, and cart icon
- [ ] Hero section with headline and CTA button
- [ ] Filter bar with brand buttons and sort dropdown
- [ ] 12 products displayed in responsive grid
- [ ] Clicking brand filter shows only relevant products
- [ ] Sort changes product order by price
- [ ] Add to Cart button adds item to cart
- [ ] Cart sidebar shows added items with quantities
- [ ] Cart total calculates correctly
- [ ] Cart persists after page refresh
- [ ] Responsive on mobile, tablet, desktop
- [ ] Smooth animations and hover effects
