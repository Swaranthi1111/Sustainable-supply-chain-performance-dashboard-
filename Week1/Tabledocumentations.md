1. Inventory Table

Objective: To display data related to inventory management.
Product Type:

1. Extracted product type information from the inventory dataset.

2. Cleaned the data using Power BI’s query editor to remove duplicates or null values.

3. Added the column to the table visualization to categorize inventory by product type.

SKU:

1. Retrieved SKU (Stock Keeping Unit) details from the dataset.

2. Ensured SKUs were unique for each product type.

3. Included the SKU column in the table for easy product identification.

Availability:

1. Added the "availability" column from the dataset.

2. Used conditional formatting to highlight low stock levels (e.g., red for critical stock).

Number of Products Sold:

1. Calculated the total products sold using a DAX measure.

2.Included the column to monitor sales performance.

Customer Demographics:

1. Filtered the dataset to display data segmented by age group, location, or preferences.

2. Used slicers for dynamic filtering based on demographic attributes.

Stock Levels:

1. Pulled the stock level data from the dataset.

2. Used bar charts alongside the table to visualize current stock levels.

Lead Times:

1. Added the lead time column to track the duration between order placement and delivery.

2. Sorted the column in ascending order for better analysis.

Order Quantities:

1. Calculated total order quantities from the dataset using a sum function.

2. Visualized the order quantities using a line chart.

Revenue Generated:

1. Created a calculated column to multiply the price per unit by the number of units sold.

2. Included it in the table to monitor financial performance.

2. Manufacturing Table

Objective: To provide insights into manufacturing data.

Steps for Subtopics:

Product Type:

1. Categorized manufacturing data by product type.

2. Filtered the dataset to focus on specific product categories.

SKU:

1. Mapped SKUs to corresponding product types.

2. Verified consistency between manufacturing and inventory datasets.

Production Volumes:

1. Extracted production volume data to monitor manufacturing output.

2. Used conditional formatting to highlight production shortfalls.

Manufacturing Lead Time:

1. Calculated average manufacturing lead times using DAX measures.

2. Displayed trends over time using a line chart.

Manufacturing Costs:

1. Imported cost-related data and included it in the table.

2. Analyzed cost patterns to identify areas for optimization.

Inspection Results:

1. Added a column for inspection outcomes (e.g., pass/fail).

2. Used data bars to visualize quality control metrics.

Defect Rates:

1. Calculated defect rates as a percentage of total production.

2. Highlighted high-defect SKUs using conditional formatting.

3. Supplier Table

Objective: To list supplier-related details for better supply chain management.

Steps for Subtopics:

Supplier Name:

1. Imported supplier names from the dataset.

2. Verified supplier data for accuracy and completeness.

Location:

1. Geocoded supplier locations using Power BI’s mapping visualization.

2. Added filters for location-based analysis.

Lead Time:

1. Extracted lead time data for each supplier.

2. Used a scatter plot to compare lead times across suppliers.

Transportation Modes:

1. Categorized data based on transportation methods (e.g., air, sea, road).

2. Used pie charts to visualize transportation mode distribution.

Routes:

1. Mapped supplier routes using a combination of location and transportation data.

2. Displayed route efficiency using line visualizations.

4. Supply Chain Table

Objective: To provide a comprehensive overview of supply chain metrics.

Steps for Subtopics:

Product Type:

1. Linked supply chain data with inventory and manufacturing datasets.

2. Created a unified product type column for consistency.

SKU:

1. Verified SKUs across supply chain data to ensure integrity.

2. Merged SKU data with related tables for a complete view.

Price:

1. Imported pricing data from the dataset.

2. Used conditional formatting to highlight high-value products.

Availability:

1. Calculated real-time product availability by combining stock and shipment data.

2. Displayed availability trends using a clustered column chart.


Revenue Generated:

1. Calculated revenue using sales data and added it to the table.

2. Used bar charts to compare revenue across product categories.

Shipping Costs and Times:

1. Analyzed shipping costs and times for different carriers.

2. Used slicers for dynamic filtering by carrier or location.

Supplier Details:

1. Linked supplier names, locations, and lead times from the supplier table.

2. Displayed supplier performance metrics in the visualization.
