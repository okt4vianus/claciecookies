# Clacie Cookies

Selling soft cookies with premium ingredients. Crafted with Purpose in Minahasa, Delivered in Care

## Table of Contents

- [Links](#links)
- [UI Designs](#ui-designs)
- [Steps](#steps)
- [Feature](#feature)

## Links

- Website

  - Frontend: [claciecookies.com](https://claciecookies.com)
  - Backend API: [api.claciecookies.com](https://api.claciecookies.com)

- Repositories

  - General : <https://github.com/okt4vianus/claciecookies>
  - Frontend-Web: <https://github.com/okt4vianus/claciecookies-web>
  - Backend-API: <https://github.com/okt4vianus/claciecookies-api>

- Inspirations:
  - Protein Bakery: <https://proteinbakery.com/>

## UI Designs

- Figma: <https://figma.com>

## Steps

- Products
- Authentication
- Cart
- Address & Check out
- Payment
- Order

## Feature

- Home page
  - Hero section
  - Products catalog
    - Inspirations: <https://proteinbakery.com/collections/cookies>
- All Products page
- One product page
  - Multiple images
    - Stage 1 - Collected in Google Drive first
    - Stage 2 - <https://uploadcare.com/>
  - Name
  - Price in rupiah
  - Description in text / html
  - Quantity increment/decrement input (no need backend)
  - Add to cart button
- Shopping cart page
  - Layout
    - Stage 1 - New page
    - Stage 2 - Side bar
  - List of product in the cart
    - Image
    - Name
    - Price in rupiah
    - Subtotal
    - Quantity increment/decrement input (min 1 disable decrement)
    - Remove from cart button
  - Total price
  - Link: checkout button
  - Link: continue shooping, go to product catalog
- Checkout page
  - Order summary
    - Product item to buy
    - Grand total of all product item to buy
    - Shipping cost
  - Shipping address form
    - Profile: Name, email, phone
    - Address: Street address, street address details, city, province, postal code, country
    - Use combobox for province, city & postal code
    - Shipping: GoSend, Express, Pos Indonesia, JNE, J&T
    - Payment method:
      - Manual: Bank transfer, COD
      - Auto: QRIS, Debit Card, etc
  - without login (next phase)
- Payment page
  - Total to pay
  - Payment method
  - Payment status
  - Payment confirmation
  - Payment receipt
- Dashboard / order history page
  - List of orders
    - Order id
    - Order date
    - Order status
    - Order total
  - Order detail page
    - Order id
    - Order date
    - Order status
    - Order total
    - Shipping address
    - Payment method
    - Product items in the order
- Register
- Login
- Dashboard
  - Profile
    - Name
    - Email
    - Phone
    - Address
  - Order history
  - Cart
