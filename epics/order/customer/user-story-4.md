## As a customer, I want to view the checkout page, so that I can add my address and payment information

### Acceptance Criteria:

#### Access to Checkout Page:

- Users can navigate to the checkout page by clicking a "Proceed to Checkout" button on the cart page
- Redirect guest users to a login/registration page or offer a "Continue as Guest" option if applicable

#### Checkout Page Header:

- The page header must contain a stepper component: Cart -> Details -> Payment -> Review

#### Shipping Address Section:

- Users must be able to input or select a saved shipping address
- Required fields include:

  - Full Name
  - Address Line 1 and Line 2 (optional)
  - City
  - State/Province/Region
  - ZIP/Postal Code
  - Country (dropdown)
  - Phone Number

- Display a checkbox for "Billing address is the same as shipping address."

#### Payment Information Section:

- Provide payment options (e.g., credit/debit card, PayPal, digital wallets).
- For card payments, require:

  - Cardholder Name
  - Card Number
  - Expiry Date (MM/YY format)
  - CVV/CVC Code

- Validate card details in real time with error messages for incorrect inputs

#### Order Summary Section:

- Display a summary of the items in the cart, including:

  - Product name and quantity
  - Price per item and subtotal
  - Taxes (if applicable)
  - Shipping cost (if applicable)
  - Total amount payable

#### Discount Code Option (Optional):

- Include a field for users to apply discount codes or coupons
- Validate and display the updated total upon application

#### Review and Confirm Button:

- Provide a clear "Place Order" or "Confirm Purchase" button at the bottom
- Display a summary of inputted details before final submission

#### Error Handling:

- Display an error message for incomplete or invalid address or payment details
- Example: "Please fill out all required fields correctly."
- Show a fallback message for unexpected errors: "Unable to process your request. Please try again."

#### Responsive Design:

- Ensure the checkout page is fully responsive, with all sections accessible on desktops, tablets, and mobile devices

#### Performance:

- The checkout page must load within 2 seconds, and interactions should not introduce delays beyond 1 second

#### Security Measures:

- Use HTTPS to encrypt data transmitted on the checkout page
- Do not display or store sensitive payment information (e.g., CVV) after submission

#### Guest Checkout Option:

- Allow guest users to complete checkout without creating an account, but provide an optional "Create an account" checkbox for convenience

#### Save Details for Future Use (Optional):

- For logged-in users, provide an option to save addresses and payment information securely for future purchases

#### Order Confirmation:

- After placing an order, redirect users to an order confirmation page with:

  - Order ID
  - Estimated delivery date (if applicable)
  - Summary of the order
