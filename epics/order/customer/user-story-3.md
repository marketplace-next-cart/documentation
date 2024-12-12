## As a customer, I want to view the cart page, so that I can see my cart details and proceed to the checkout page

### Acceptance Criteria:

#### Access to Cart Page:

- Customers must be able to access the cart page by clicking "View Cart" button from cart dialog

#### Cart Page Header:

- The page header must contain a stepper component: Cart -> Details -> Payment -> Review

#### Cart Item Details:

- Each product in the cart must display the following details:

  - Product name (linked to the product details page)
  - Product image
  - Selected options (e.g., size, color)
  - Unit price
  - Quantity (editable with increment and decrement buttons)
  - Subtotal for the product (unit price × quantity)

#### Cart Summary:

- The cart page must include a summary section displaying:

  - Total number of items
  - Subtotal amount
  - Taxes (if applicable)
  - Shipping cost (if calculable at this stage)
  - Grand total amount

#### Update Cart Option:

- If quantity changes are made, the cart must automatically or manually recalculate totals upon clicking an "Update Cart" button
- Display a success message: "Cart updated successfully."

#### Proceed to Checkout:

- The cart page must have a prominently displayed "Proceed to Checkout" button that navigates to the checkout page

#### Remove Item Option:

- Users can remove individual products from the cart using a "Remove" or "Delete" button for each product
- Display a confirmation prompt before removal
- Recalculate totals after removal

#### Stock Validation:

- Validate product availability and stock levels for each item in the cart
- If a product is out of stock, display a message: "This item is currently out of stock."

#### Empty Cart State:

- If the cart is empty, display a message: "Your cart is empty."
- Include a "Continue Shopping" button, that redirect to products list

#### Error Handling:

- If cart data cannot be loaded, display an error message: "Unable to load cart details. Please try again later."

#### Responsive Design:

- Ensure the cart page is fully responsive, functioning well on desktops, tablets, and mobile devices

#### Performance:

- The cart page must load within 2 seconds, even with multiple items in the cart

#### Optional Features:

- Show a "Recently Viewed Products" section to encourage further shopping
- Include a discount code input field for users to apply coupons
- Highlight any applicable promotions or offers based on the cart contents

#### Guest and Logged-In Users:

- For guest users, the cart must persist for the current session.
- For logged-in users, the cart must sync across devices.

#### Navigation to Product Details:

- Clicking on a product name or image in the cart redirects the user to the product details page
