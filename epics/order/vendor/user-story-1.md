## As a vendor, I want to view orders, so that I can process them

### Acceptance Criteria:

#### Order List Display:

- Page must contain 4 tabs: All, Pending, Completed, Cancelled and Refunded
- Products must have a bulk edit option for status or cancel
- The table must have the functionality to hide columns
- The orders page must display a list of all orders with the following details for each order:

  - Order ID
  - Customer full name
  - Order date and time
  - Order status (Pending, Processing, Shipped, Completed, Cancelled)
  - Total order amount
  - Delivery option
  - Payment status (Paid, Pending, Failed)
  - Actions: View, Delete

#### Sorting Options:

- Vendors can sort the order list by:

  - Customer full name (alphabetically)
  - Newest to oldest or oldest to newest
  - Order amount (low to high or high to low)

#### Search and Filters:

- Provide a search box to find orders by customer full name, ID, product name within the order
- Allow filtering by order status (Pending, Shipped)
- Allow filtering by payment status
- Allow filtering by date range
- Allow filtering by delivery option

#### Pagination:

- If there are many orders, implement pagination
- Display the total number of orders and pages

#### Order Status Management:

- Vendors can update the status of an order (from "Pending" to "Shipped")
- Provide a dropdown or button group for status changes with confirmation prompts

#### Responsive Design:

- Ensure the orders page is fully responsive, functioning well on all devices, including desktops, tablets, and mobile phones

#### Performance:

- The orders list should load within 2 seconds, even with a large number of orders.

#### Error Handling:

- If orders cannot be retrieved, display an error message (e.g., "Unable to load orders. Please try again later.")

#### Optional Features:

- Allow vendors to export orders list as a CSV file for offline management
- Allow vendors to import orders list as a CSV file for offline management

#### Notifications (Optional):

- Provide a notification system that alerts vendors to new orders or updates to existing orders.

#### Empty State:

- If there are no orders, display a message like: "You don't have any orders yet" and suggest promoting their products to attract customers
