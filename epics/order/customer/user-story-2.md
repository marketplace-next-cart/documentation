## As a customer, I want to update a product in the cart, so that I can easily change the cart content

### Acceptance Criteria:

#### Product Information in Cart:

- Each product entry in the cart must include:

  - Product name
  - Product image
  - Selected options (e.g., size, color)
  - Unit price
  - Current quantity
  - Subtotal (unit price × quantity)

#### Editable Quantity:

- Customers can update the quantity of any product using:

  - A numeric input field
  - Increment (+) and decrement (–) buttons

#### Stock Validation:

- The system must validate that the updated quantity does not exceed available stock
- If stock is exceeded, display an error message: "Only X items available in stock."

#### Save Updates:

- Changes to the product quantity are saved automatically or after clicking an "Update Cart" button (based on implementation)
- Display a success message: "Cart updated successfully."

#### Remove Product Option:

- Each product entry should include a "Remove" or "Delete" button
- Clicking the button removes the product from the cart after confirmation

#### Price Recalculation:

- Updating the quantity or removing a product must trigger real-time recalculation of:

  - Subtotal for the product
  - Cart total and tax (if applicable)

#### Error Handling:

- Display an error message if the update process fails: "Unable to update the cart. Please try again."
- Handle scenarios where the product is no longer available in stock (e.g., "This product is no longer available")

#### Cart Summary Update:

- Update the cart icon in the header with the new total items count and value after changes

#### Responsive Design:

- Ensure the cart page and update functionality work seamlessly on all devices (desktop, tablet, and mobile)

#### Performance:

- Updates to the cart (e.g., quantity changes or removals) should reflect within 1 second

#### Optional Features:

- Highlight recently updated products in the cart for clarity
- Provide an "Undo" option after removing a product for a limited time

#### Persist Cart Updates:

- For logged-in users, ensure cart updates are saved to their account and accessible across devices
- For guest users, persist changes for the current session

#### Empty Cart State:

- If all products are removed, display a message: "Your cart is empty."
- Include a link to continue shopping
