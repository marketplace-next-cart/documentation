## As a customer, I want to search products by different categories, subcategories, and filters, so that I can explore available items and make purchasing

### Acceptance Criteria:

#### Category and Subcategory Navigation:

- Users can select a category (e.g., Electronics, Fashion) to view relevant products
- Subcategories (e.g., Laptops under Electronics) are displayed and selectable within the chosen category

#### Filter Options:

Users can filter products within categories or subcategories by:

- Price Range: Slider or input for minimum and maximum price
- Brand: List of brands relevant to the selected category
- Ratings: Filter by minimum customer rating (e.g., 4 stars and above)
- Discounts: Show products with ongoing discounts (e.g., "10% off or more")
- Availability: Filter by stock status (e.g., "In Stock")

#### Filtering Results Display:

- Display all products matching the selected categories, subcategories, and filters
- The page should contain 21 products, if there are more products pagination and the "Load more" button should be displayed

#### Card Layout:

- Thumbnail image
- Product name
- Price
- Rating and review count
- "Add To Cart" icon button
- On hover, available Preview and Add to favorite icon buttons
- Discount label (if applicable)

#### Users can sort the search results by:

- Price: Low to high, high to low
- Ratings: High to low
- New arrivals

#### No Results Handling:

If no products match the selected categories, subcategories, or filters, display a user-friendly message (e.g., "No products found. Please try adjusting your filters.")

#### Clear Filters Button:

Include a "Clear Filters" button to reset all applied filters and return to the full product list

#### Change layout view

- Users should have the possibility to change products layout between Grid and List

#### Performance:

- Search and filter results should load within 2 seconds for a smooth user experience
- Use lazy loading or infinite scroll for large result sets to optimize performance
