## As a customer, I want to add a product to the cart, so that I can create an order

### Acceptance Criteria:

#### Add to Cart Button:

- Each product should have a visible "Add to Cart" button on product listing and product details pages
- If the product has variants (e.g., size or color), clicking "Add to Cart" should prompt the user to select a variant before adding the product

#### Product Addition to Cart:

- When a customer clicks "Add to Cart," the selected product is successfully added to their shopping cart
- A confirmation message is displayed: "Product added to your cart."

#### Cart Icon Update:

- The shopping cart icon (usually in the header) updates to show the current number of items in the cart
- Total cart value is optionally displayed in the dropdown or on hover

#### View Cart Option:

- After adding a product, provide an option to "View Cart" or "Continue Shopping."
- Clicking "View Cart" navigates the customer to the cart page

#### Duplicate Product Handling:

- If a product is already in the cart and the customer adds it again, the quantity increases instead of duplicating the item
- Display a confirmation message like: "Quantity updated in your cart."

#### Validation for Stock:

- If the requested quantity exceeds available stock, display an error message: "Only X items available in stock."

#### Error Handling:

- If adding the product fails due to any reason, display an error message: "Unable to add the product to your cart. Please try again."

#### Guest and Logged-in customers:

- Guest users can add products to the cart without logging in, but the cart persists for the session only
- Logged-in users’ carts are saved for later access across devices

#### Cart Accessibility:

- The cart must be easily accessible from any page, typically through a shopping cart icon in the header

#### Responsive Design:

- Ensure the "Add to Cart" button and cart functionality work seamlessly on all devices (desktop, tablet, and mobile)

#### Performance:

- Adding a product to the cart should complete within 1 second to ensure a smooth user experience

#### Optional Features:

- Show a quick preview or dropdown cart when a product is added, summarizing items in the cart and total cost
- Highlight related products or upsell suggestions after adding to the cart

#### Out-of-Stock Products:

- Disable the "Add to Cart" button for out-of-stock products
- Display a message: "Out of Stock" or "Notify Me When Available."
