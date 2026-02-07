## **Exploratory Data Analysis of Customer Behavioral Trends and Operational Performance for Food Hub**

### **Project Overview**

This project involved a comprehensive analysis of customer order data for Food Hub, a food delivery platform, to identify the key drivers of customer satisfaction and operational efficiency. By utilizing Python for data cleaning and exploratory data analysis (EDA), I examined the relationships between order costs, cuisine types, delivery durations, and customer ratings. The analysis successfully identified critical thresholds in delivery times that directly impact service ratings, providing a data-driven foundation for enhancing Food Hub’s competitive positioning.

### **Business Understanding**

The primary stakeholders for this project are Food Hub’s operations and vendor management teams. In the 2026 food delivery market, customer retention is highly sensitive to delivery speed and service reliability. Research suggests that a significant percentage of customers will switch platforms following a single poor delivery experience.

The business problem focused on identifying which operational variables—specifically delivery time and order value—most strongly correlate with high customer ratings. By answering these questions, Food Hub can optimize its logistics, improve vendor partnerships with high-performing restaurants, and design targeted strategies to increase repeat purchase rates.

### **Data Understanding**

The analysis was performed on a dataset of order-level records containing both numerical and categorical features.

* **Key Variables:** Customer ratings, delivery times, order costs, cuisine types, and restaurant identifiers.
* **Data Preparation:** The process involved extensive reformatting of data types, de-duplication, and the handling of missing values.
* **Feature Engineering:** I derived new features such as "Delivery Time Categories" and "Order Value Groupings" to facilitate a more granular analysis of performance tiers.
* **Limitations:** The dataset represents a snapshot of historical orders; therefore, it may not account for external variables such as extreme weather events or localized traffic disruptions that could skew delivery performance metrics.
<img width="546" height="237" alt="Screen Shot 2026-01-23 at 00 12 24" src="https://github.com/user-attachments/assets/bcd2c01e-f48f-4953-9e9f-0d6d0e74fee9" />

### **Modeling and Evaluation**

This project utilized **Descriptive Statistics** and **Multivariate Exploratory Data Analysis** to evaluate platform performance. While not a predictive modeling project, the data was evaluated using the following analytical frameworks:

* **Trend Analysis:** Used distribution plots and bar charts to isolate the impact of delivery duration on customer satisfaction scores.
* **Segment Evaluation:** Benchmarked performance metrics across different cuisine types to identify which food categories are most resilient to longer delivery times.
* **Correlation Metrics:** Analyzed the relationship between food quality ratings and overall order ratings to determine if delivery speed could "offset" or "diminish" the perception of food quality.
<img width="456" height="393" alt="Screen Shot 2026-01-23 at 00 15 50" src="https://github.com/user-attachments/assets/5e88c1b8-c724-4c48-9131-f7fb97e38d34" />
<img width="456" height="393" alt="Screen Shot 2026-01-23 at 00 15 50" src="https://github.com/user-attachments/assets/684a3c6d-9290-4dad-a173-1d04c24d9147" />
<img width="495" height="342" alt="Screen Shot 2026-01-23 at 00 04 02" src="https://github.com/user-attachments/assets/47328c22-7039-428c-ae7b-a5047ea1eb43" />
<img width="499" height="320" alt="Screen Shot 2026-01-23 at 00 16 28" src="https://github.com/user-attachments/assets/a63f86e9-5a8e-486d-9eba-d07f5e0f9a69" />

### **Conclusion**

The analysis concludes that delivery punctuality and consistent food quality are the most significant predictors of high customer ratings. To solve the identified business problems, I recommend that Food Hub implement a **"Priority Vendor" program** for restaurants with high food ratings but suboptimal delivery times, providing them with enhanced logistics support.

**Future Steps:**

* **Predictive Analytics:** I plan to build a **Logistic Regression or Random Forest model** to predict the likelihood of a customer providing a 5-star rating based on real-time order characteristics.
* **Personalization:** Incorporate customer-level behavioral data to create a recommendation engine that prioritizes restaurants with historically high reliability for specific users.
