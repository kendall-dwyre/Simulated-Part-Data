# Parts Inventory Optimization for Farming Operations

## **Project Overview**
This project is focused on optimizing the parts inventory and purchasing process for a farming operation. By analyzing parts data, the goal is to improve efficiency, reduce costs through bulk purchasing, and minimize downtime due to stockouts. The dataset tracks various parts used in the farming operation, including oil filters, tires, hydraulic hoses, and more, with details such as stock levels, usage rates, supplier information, and bulk discount availability.

## **Dataset Explanation**
The dataset consists of 1,000 rows of part-related data, including:
- **Part ID**: A unique identifier for each part.
- **Part Name**: The name of the part (e.g., oil filter, tire, hydraulic hose).
- **Part Number**: A specific number identifying the part.
- **Quantity on Hand**: The number of parts currently in stock.
- **Reorder Threshold**: The minimum stock level at which a part should be reordered.
- **Last Ordered Date**: The last time the part was ordered.
- **Average Monthly Usage**: The average number of parts used per month.
- **Supplier**: The supplier providing the part.
- **Cost per Unit**: The cost of each unit of the part.
- **Lead Time Days**: The time it takes for a part to arrive after being ordered.
- **Bulk Discount Availability**: Indicates whether a bulk discount is available for the part.

## **Project Goals**
The primary goals of this project include:
1. **Optimizing the Timing of Parts Reordering**: Ensuring parts are reordered before they run out, based on usage rates and lead times.
2. **Taking Advantage of Bulk Discounts**: Identifying parts where bulk discounts are available and making recommendations to reduce costs by purchasing in bulk.
3. **Reducing Operational Downtime**: By accurately timing part orders and maintaining sufficient stock, we aim to reduce downtime caused by parts shortages.

## **Process**
### Step 1: Data Collection
- The dataset was generated to simulate parts tracking for a farming operation. The data includes relevant fields like part usage rates, reorder thresholds, and supplier information.

### Step 2: Data Analysis
- **Bulk Discount Analysis**: The dataset was analyzed to identify parts that offer bulk discounts and calculate the potential savings from purchasing these parts in bulk.
- **Optimal Reorder Points**: Using the lead time for each part and its average monthly usage, optimal reorder points were calculated to ensure timely reordering and minimize stockouts.
- **Usage and Cost Trends**: Parts were prioritized based on their total usage and cost per unit to ensure the most critical parts are always in stock.

### Step 3: Insights Generation
- We used Python to conduct in-depth analysis, focusing on the most frequently used parts and those with the greatest savings potential when ordered in bulk. Calculations of reorder points were based on actual part usage and lead time data.

## **Key Insights**
1. **Significant Cost Savings in Bulk Orders**:
   - **Tires**: By purchasing tires in bulk, the operation can save around $91,030 annually. With high usage and frequent reordering needs, bulk discounts on tires can result in significant cost reductions.
   - **Air Filters**: Purchasing air filters in bulk can save approximately $79,921. Given their high usage, bulk ordering would lead to consistent cost savings.
   - **Hydraulic Hoses and Oil Filters**: These parts also offer substantial savings ($74,945 and $62,510, respectively) when ordered in bulk.

2. **Reorder Points to Avoid Stockouts**:
   - By calculating the reorder points, we determined that:
     - **Tires** should be reordered when stock drops to around 5 units to avoid running out.
     - **Oil Filters** should be reordered when stock reaches around 6 units.
     - Reordering these parts based on lead times will ensure they are always available when needed, reducing operational downtime.

3. **Optimizing Inventory Management**:
   - By implementing an inventory tracking system and monitoring key parts with bulk discounts, the farming operation can significantly reduce trips to town, saving on fuel costs and time.
   - Bulk purchasing not only saves money but also ensures parts are available well before they are needed, reducing inefficiencies.

## **Value and Usefulness**
- **Cost Efficiency**: The insights from this analysis demonstrate that bulk purchasing could save thousands of dollars per year. This is particularly important in farming operations where keeping costs down is critical to profitability.
- **Operational Efficiency**: By identifying optimal reorder points and maintaining proper stock levels, the operation will experience fewer disruptions due to missing parts. This ensures that machinery remains operational, minimizing downtime.
- **Long-Term Sustainability**: The strategy of bulk purchasing, coupled with data-driven inventory management, makes the operation more sustainable by reducing unnecessary trips and resource waste.

## **Conclusion**
By using data analytics to optimize parts inventory, this project helps the farming operation reduce costs, improve efficiency, and prevent costly downtime. These insights are directly applicable to any agricultural business looking to streamline its parts management processes and enhance operational performance.
