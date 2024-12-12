## As a vendor, I want to view the product list, so that I can see all my products

### Acceptance Criteria:

#### Display Product Information:

- Page must contain 4 tabs: All, Active, Inactive, and Draft
- Products must have a bulk edit option for status and availability
- The table must have the functionality to hide columns
- The product list must include the following details for each product:

  - Thumbnail image
  - Product Name
  - Category
  - Brand
  - Price (original and discounted, if applicable)
  - Stock quantity
  - Product status ("Published", "Draft")
  - Availability ("In Stock", "Out of Stock", "Low stock")
  - Actions: Edit, View, Delete, Duplicate

#### Sorting Options:

- Vendors can sort the product list by:

  - Product name (alphabetically)
  - Category (alphabetically)
  - Brand (alphabetically)
  - Price (low to high or high to low)
  - Stock quantity (low to high or high to low)
  - Product status (alphabetically)
  - Availability (alphabetically)

#### Search and Filters:

- Provide a search box to find products by name, SKU, or category
- Allow filtering by product status ("Published", "Draft")
- Allow filtering by product availability ("In Stock", "Out of Stock", "Low stock")
- If filtering or searching doesn't have products show a message: "No products match your query"

#### Pagination:

- If the vendor has a large number of products, implement pagination
- Display the total number of products and pages

#### Responsive Design:

- Ensure the product list is easily navigable on all devices, including mobile, tablet, and desktop

#### Performance:

- The product list should load within 2 seconds, even for vendors with 100+ products

#### Error Handling:

- Display an appropriate error message if the product list cannot be retrieved (e.g., "Unable to load your products. Please try again later.")

#### Confirmation for Actions:

- Require confirmation for critical actions like deleting a product ("Are you sure you want to delete this product?")

#### Optional Features:

- Allow vendors to export their product list as a CSV file for offline management

#### Empty State:

- If the vendor has no products, display an empty state with a message ("You haven't added any products yet.") and a call-to-action button ("Add Product")
