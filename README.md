# Parts Inventory Optimization for Farming Operations Using Six Sigma Methodology

## **Project Overview**
This project applies Six Sigma supply chain principles to optimize the parts inventory and purchasing process for a farming operation. The goal is to streamline operations, reduce costs through bulk purchasing, and minimize downtime due to stockouts. By following the Six Sigma DMAIC (Define, Measure, Analyze, Improve, Control) framework, the project identifies inefficiencies and implements data-driven improvements. The dataset tracks various parts used in the operation, including oil filters, tires, hydraulic hoses, and more, with details on stock levels, usage rates, supplier information, and bulk discount availability.

## **Six Sigma DMAIC Process**

### **1. Define**
- **Problem Statement**: The farming operation has no formal process to manage parts inventory, resulting in inefficiencies such as frequent trips to town, missed bulk purchasing opportunities, and downtime due to stockouts.
- **Goal**: To improve the efficiency of parts management by optimizing reorder timing, leveraging bulk purchasing, and minimizing operational disruptions.

### **2. Measure**
- **Data Collection**: A dataset was generated to track key part metrics including:
    - **Part Name**: Describes the part (e.g., oil filter, tire).
    - **Quantity on Hand**: The current stock level.
    - **Reorder Threshold**: The level at which the part should be reordered.
    - **Average Monthly Usage**: The average monthly consumption of each part.
    - **Lead Time**: The number of days between ordering and receiving the part.
    - **Bulk Discount Availability**: Identifies whether bulk discounts are available.
- **Current State**: Data showed frequent trips to town for parts, occasional stockouts, and underutilization of bulk discounts.

### **3. Analyze**
The data analysis focused on identifying inefficiencies in the current parts management process. Specifically, we analyzed:
- **Part Usage**: Prioritizing parts with high usage that often run low in stock.
- **Lead Times**: Calculating how long it takes for each part to arrive and adjusting reorder points accordingly.
- **Bulk Discounts**: Evaluating the potential cost savings from bulk purchasing for parts that are frequently used and eligible for discounts.

Using Python, the data was aggregated and sorted based on usage, lead time, and potential savings.

### **4. Improve**
Based on the analysis, the following improvements were recommended:
- **Bulk Purchasing Strategy**: For frequently used parts with available bulk discounts, such as tires, air filters, and oil filters, the data suggests purchasing in bulk can lead to significant savings (up to $91,030 for tires alone).
- **Reorder Point Optimization**: Reorder points were calculated using average monthly usage and lead time to ensure that parts are ordered before running out, preventing stockouts and minimizing downtime.
  - For example, tires should be reordered when stock falls to 5 units to avoid shortages, while oil filters should be reordered at 6 units.

### **5. Control**
To maintain the improved system, control mechanisms were proposed:
- **Inventory Management System**: Implementing a simple inventory tracking system that includes reorder alerts when parts fall below their optimal levels.
- **Bulk Discount Monitoring**: Regularly monitoring suppliers for bulk discount opportunities and automating bulk orders when significant savings can be realized.
- **Process Documentation**: Establishing standard operating procedures (SOPs) for ordering and maintaining parts stock levels to ensure consistency and prevent regression to inefficient practices.

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

## **Key Insights and Results**
1. **Cost Savings through Bulk Orders**:
   - **Tires**: Potential annual savings of $91,030 by purchasing tires in bulk.
   - **Air Filters and Hydraulic Hoses**: Significant savings ($79,921 and $74,945 respectively) when ordered in bulk.
   - **Oil Filters**: Savings of approximately $62,510 from bulk purchases.

2. **Optimized Reorder Points**:
   - **Tires**: Should be reordered when stock drops to 5 units to avoid stockouts.
   - **Oil Filters**: Reorder when stock reaches 6 units to maintain availability.
   - These reorder points ensure that parts are ordered well before they run out, avoiding operational delays.

3. **Supply Chain Efficiency**:
   - By implementing these strategies, the farming operation will reduce unnecessary trips to town, minimize downtime, and save significantly through bulk purchasing and optimized inventory management.

## **Value and Usefulness**
The application of Six Sigma principles in this project demonstrates how data-driven insights can transform parts management processes in farming operations:
- **Cost Efficiency**: Bulk purchasing leads to thousands of dollars in savings annually, particularly for high-usage parts.
- **Operational Efficiency**: The analysis provides clear guidelines on when to reorder parts to prevent stockouts and reduce downtime, ensuring machinery remains operational.
- **Sustainable Practices**: By optimizing purchasing decisions and inventory management, the operation can significantly reduce fuel costs, time, and waste associated with frequent trips to town for parts.

## **Conclusion**
This project applied the Six Sigma DMAIC methodology to improve parts management in a farming operation. By identifying inefficiencies and implementing data-driven improvements, the operation will see reduced costs, improved operational uptime, and enhanced long-term sustainability. These results can be applied to other agricultural businesses seeking to streamline their parts supply chain and improve efficiency.

