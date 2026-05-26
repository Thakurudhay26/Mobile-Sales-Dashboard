# 📱 Mobile Sales Analytics Dashboard

A dynamic, interactive data visualization tool built to explore mobile sales performance—focusing on brand metrics, geographical distribution, customer behavior, and transaction trends.

## Short Description / Purpose
The Mobile Sales Analytics Dashboard is a visually engaging and highly analytical Power BI report built as part of the YouTube Master Class on Power BI by Satish Dhawale. Designed to mimic real-world business intelligence environments, this dashboard helps retailers and analysts evaluate performance trends across major mobile brands, transaction types, customer satisfaction levels, and payment methods.

---

## Tech Stack
The dashboard was built using the following tools and technologies:
* 📊 **Power BI Desktop** – Main data visualization platform used for report creation and canvas design.
* 📂 **Power Query** – Data transformation, cleaning, and profiling layer used to prepare raw datasets.
* 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures, dynamic time-intelligence formatting, and custom KPIs.
* 📝 **Data Modeling** – Star schema optimization establishing robust relationships among datasets to support seamless cross-filtering.
* 📁 **File Format** – `.pbix` for the active development model and `.jpg`/`.png` for previews.

---

## Data Source
* **Source:** Provided by Satish Dhawale (Power BI Master Class Dataset).
* **Fields Included:** Brand (Apple, OnePlus, Samsung, Vivo, Xiaomi), City/Geographical Locations (India-wide distribution including Delhi, Mumbai, Hyderabad, etc.), Total Sales, Total Quantity, Transactions, Average Order Value, Customer Ratings (1-5 star scale), Day Name, and Month.

---

## Features / Highlights

### • Business Problem
Mobile retailers generate massive amounts of daily sales data across various channels, regions, and brands. Without centralizing this information, recognizing consumer patterns, identifying underperforming regions, tracking customer satisfaction drops, or pinpointing peak sales days becomes highly inefficient. 

### • Goal of the Dashboard
To deliver a responsive visual control center that:
* **Monitors Core Growth:** Tracks absolute revenue, sales volume, and transaction frequency.
* **Compares Brand Performance:** Reviews market share and performance metrics among top mobile manufacturers.
* **Analyzes Payment Infrastructure:** Understands how customers prefer to pay to optimize transaction checkout systems.
* **Evaluates Regional and Temporal Success:** Pins down exactly which cities and days of the week drive the most profit.

### • Walkthrough of Key Visuals
* **High-Level KPI Cards (Top Header):** Displays immediate high-level business health values: *Total Sales ($769M)*, *Total Quantity Sold (19K)*, *Total Transactions (4K)*, and *Average Transaction Value (40K)*.
* **Interactive Month Slicer (Left Sidebar):** A vertical button panel mapping January through December, letting users dynamically filter the entire dashboard by specific months.
* **Total Sales by City (Interactive Bubble Map):** An integrated geographical map highlighting sales hot-spots across India (e.g., Ludhiana, Delhi, Patna, Hyderabad, Mumbai, Coimbatore), where bubble size correlates directly with revenue.
* **Total Quantity by Month (Trend Line):** A continuous line chart tracing inventory movement month-over-month, showing steady demand peaks around March and July.
* **Customer Ratings Breakdown (Funnel Chart):** Displays customer feedback volume categorized from 1 to 5 stars, highlighting that 5-star ratings form the largest volume block.
* **Payment Method Distribution (Pie Chart):** Breaks down transactions by payment types: *UPI (26.25%)*, *Debit Card (25.89%)*, *Cash (25.03%)*, and *Credit Card (22.83%)*—showing remarkably balanced transaction preferences.
* **Top 3 Mobile Sold (Horizontal Bar Chart):** Showcases the top three highest-grossing individual handset models (iPhone SE at 60M, OnePlus at 58M, Galaxy N at 56M).
* **Total Sales by Day Name (Area Trend Chart):** Tracks cumulative sales performance through days of the week, clearly pinpointing Saturday and Monday as primary revenue drivers.
* **Brand-wise Metrics (Granular Data Table):** A detailed table at the bottom left ranking top brands (Apple, OnePlus, Samsung, Vivo, Xiaomi) directly against their exact sales, quantities, and transaction counts.

### • Business Impact & Insights
* **Inventory Allocation:** By looking at the *Total Sales by Day Name* and *Quantity by Month*, logistics managers can prep stock supply chains ahead of high-volume days (like Saturdays) and seasonal spikes.
* **Strategic Marketing:** Regional managers can see high-performing cities like Delhi and Lucknow on the map visual to scale up targeted retail marketing campaigns.
* **Payment & Checkout Optimization:** With digital payments (UPI & Debit Cards) taking up over half of the transaction share, businesses can ensure digital payment gateway uptimes are prioritized to decrease checkout friction.
* **Brand Focus:** The brand matrix table clearly shows Apple leading the pack in overall sales revenue, giving purchasing departments strong data on where to direct capital investment.

---

## Screenshots / Demos

![Mobile Sales Dashboard Preview](https://github.com/Thakurudhay26/Mobile-Sales-Dashboard/blob/main/Mobile%20Sales%20Dashboard%20Snapshot.png)
