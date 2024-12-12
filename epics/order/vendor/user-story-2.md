## As a vendor, I want to view order details page, so that I can explore information and success process it

### Acceptance Criteria:

#### Basic Order Information:

- The order details page must display:

  - Order ID
  - Order date and time
  - Order status (e.g., Pending, Processing, Shipped, Completed, Cancelled)
  - Payment status (e.g., Paid, Pending, Failed)
  - Total order amount

#### Customer Information:

- Customer name
- Email address
- Phone number
- Shipping address (with clear formatting)

#### Product Details:

- For each product in the order, display:

  - Product name
  - Product image (if available)
  - SKU or item code (if applicable)
  - Quantity ordered
  - Price per item
  - Total price for each product

#### Shipping Details:

- Shipping method selected by the customer
- Estimated delivery date (if applicable)
- Tracking number (if already shipped)

#### Order Status Update:

- Vendors can update the order status (e.g., change from "Pending" to "Shipped")
- Provide a dropdown or button group for status updates
- Include a confirmation prompt before saving changes

#### Notes and Communication (Optional):

- Display any special instructions or notes provided by the customer
- Allow vendors to add private notes for internal use

#### Downloadable Documents (Optional):

- Provide options to download:

  - Invoice
  - Packing slip

#### Error Handling:

- Display an error message if the order details cannot be retrieved (e.g., "Unable to load order details. Please try again later.")

#### Responsive Design:

- Ensure the order details page is fully responsive and accessible on all devices (desktop, tablet, and mobile)

#### Performance:

- The order details page should load within 2 seconds, even for complex orders with multiple items

#### History changes log

- Vendor must have the possibility to see history changes log

#### Bulk Order Details Access (Optional):

- If accessed from a list of orders, provide a "Next" and "Previous" button to navigate between order details without returning to the main orders page

#### Customer Communication (Optional):

- Include a button to contact the customer via email or in-app messaging regarding the order (if allowed)

#### Confirmation Messages:

- Show a success message after status updates or other actions (e.g., "Order status updated successfully.")

#### Empty or Missing Data Handling:

- If certain fields (e.g., customer phone number, shipping details) are unavailable, display "Not provided" or a similar placeholder
