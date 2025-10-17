# Swiggy Restaurant Insights Dashboard

### 1. Overview and Purpose

This dashboard provides a comprehensive, data-driven analysis of restaurant performance, customer satisfaction, and operational efficiency across key Swiggy operating cities. The goal is to offer stakeholders a clear, interactive view to identify market strengths, operational bottlenecks, and opportunities for quality improvement.

### 2. Key Performance Indicators (KPIs)

The dashboard presents four main KPIs based on the aggregate data:

| KPI | Description | Metric |
| :--- | :--- | :--- |
| **Total Restaurants** | The total number of **unique** restaurants available on the platform across all included cities. | Count (Distinct) |
| **Average Rating** | The overall average customer rating (out of 5.0) for all restaurants. | Average |
| **Average Delivery Time** | The average time (in minutes) from order placement to customer delivery (includes prep time). | Average |
| **Average Price** | The overall average price of a meal/order across the platform. | Average |

### 3. Data Source and Scope

| Detail | Description |
| :--- | :--- |
| **Source File** | `Swiggy_Restaurant_Data.xlsx` |
| **Time Period** | 2 years ago |
| **Cities Covered** | Ahmedabad, Bangalore, Chennai, Delhi, Hyderabad, Kolkata, Mumbai, Pune, Surat |
| **Key Fields Used** | ID, City, Price Teir, Avg ratings, Rating Band, Delivery time |

### 4. Interactive Components (Slicers)

The most powerful feature of this dashboard is its interactivity. All charts and KPIs respond to the slicers, allowing for deep, segmented analysis.

| Slicer | Functionality | Example Insight |
| :--- | :--- | :--- |
| **City** | Filters all data to a single city or a selection of cities. | What is the Avg Delivery Time *only* in Bangalore? |
| **Price Teir** | Filters data by restaurant price segment (Budget, Mid-Range, Premium). | How do *Premium* restaurants perform across all metrics? |
| **Rating Band** | Filters data by quality tiers (Excellent, Very Good, Good, Fair). | What is the total count of *Excellent* rated restaurants? |

### 5. Charts and Key Insights

The dashboard features four core visualizations for deep-dive analysis:

| Chart Title | Chart Type | Core Question Answered |
| :--- | :--- | :--- |
| **Top Rated Restaurants by Average Rating** | Bar Chart | Which individual restaurants are service champions? |
| **Top Rated Areas by Average Rating** | Bar Chart | Which geographical localities offer the highest quality experience? |
| **\[City Name] Restaurant Rating Distribution** | Pie Chart | What is the quality breakdown (Excellent/Good/Fair) of the restaurant inventory in a selected city? |
| **Average Delivery Time by Price Tier** | Line Chart | Is there a correlation between restaurant price and delivery speed/operational efficiency? |

### 6. Technical Notes

* **Platform:** Microsoft Excel
* **Data Model:** The dashboard utilizes the Excel Data Model to ensure all PivotTables and PivotCharts are correctly linked to the Slicers.
* **Unique Count:** The **Total Restaurants** KPI is calculated using the **Distinct Count** function to avoid counting a single restaurant multiple times for different cuisines.
* **Viewing:** It is highly recommended to view the dashboard with the **Ribbon collapsed** and **Gridlines/Headings hidden** (View Tab) for a clean, maximized presentation experience.

***

<img width="1181" height="628" alt="image" src="https://github.com/user-attachments/assets/daa9e8e9-484e-4a8f-8c67-0071b3cb45bc" />


<img width="1179" height="629" alt="image" src="https://github.com/user-attachments/assets/0d9de508-2519-46b4-8e2e-f9de528a80e7" />
