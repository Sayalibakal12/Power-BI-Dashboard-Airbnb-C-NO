## 🧾 **Project Title**

**Power-BI-Dashboard-Airbnb-C-NO**

---

## 💡 **Brief One Line Summary**

An interactive Power BI dashboard that analyzes Airbnb listings in New York City to uncover pricing trends, popular locations, and host behaviors.

---

## 📘 **Overview**

The goal of this project is to convert raw Airbnb listing data into meaningful insights using Power BI. This dashboard enables users—such as investors, hosts, and tourism analysts—to understand market dynamics, compare neighborhood performance, and monitor listing availability across NYC. By integrating key metrics and visuals, it serves as a valuable tool for data-driven decision-making.

---

## ❓ **Problem Statement**

Airbnb hosts and real estate investors face challenges in identifying the most profitable neighborhoods, optimal pricing strategies, and guest behavior trends. A centralized, interactive dashboard is needed to analyze listing performance, room types, and host activity to guide better decisions.

---

## 📂 **Dataset**

* **Source**: [Inside Airbnb NYC 2019 dataset](http://insideairbnb.com/get-the-data.html)
* **File Name**: `AB_NYC_2019.csv`
* **Key Features**:

  * `id`, `name`, `host_id`, `neighbourhood_group`, `neighbourhood`
  * `room_type`, `price`, `minimum_nights`, `availability_365`
  * `number_of_reviews`, `reviews_per_month`, `last_review`

---

## 🛠️ **Tools and Technologies**

* **Data Visualization**: Power BI
* **Data Preparation**: Power BI Power Query, DAX
* **Supporting Tools**: Excel (optional), Python (optional for preprocessing)

---

## 🧪 **Methods**

1. **Data Cleaning**:

   * Removed null values from `reviews_per_month`, `last_review`
   * Handled outliers in `price` and `minimum_nights`
   * Filtered listings with realistic availability and review counts

2. **Data Modeling**:

   * Created calculated columns: revenue, review-to-listing ratio, price band
   * Built relationships between location, room type, and pricing

3. **Visualization**:

   * Map visuals to show listing density and pricing
   * Bar/column charts for room type, price comparison
   * Slicers and filters for interactive analysis

---

## 📊 **Key Insights**

* **Manhattan** leads in listing count and average price.
* **Entire homes/apartments** earn more revenue but are less available than shared/private rooms.
* Listings with **lower minimum night requirements** have higher review volumes.
* **Brooklyn and Queens** offer cost-effective options for budget travelers.
* Hosts with multiple listings are concentrated in high-demand zones.

---

## 📈 **Dashboard/Model/Output**

The Power BI dashboard includes:

* **Map View**: Listing locations with color-coded price bands
* **Neighborhood Analysis**: Average prices and availability by borough
* **Room Type Summary**: Visual breakdown of room types by area
* **Host Activity**: Distribution of listings per host
* **Filters/Slicers**: Interactive tools for exploring data by room type, price range, and location

---

## 🧭 **How to Run This Project?**

1. Open Power BI Desktop
2. Load the `.pbix` file: `Power-BI-Dashboard-Airbnb-C-NO.pbix`
3. If dataset isn't embedded, connect to `AB_NYC_2019.csv`
4. Use the slicers to:

   * Filter by `Neighbourhood Group`, `Room Type`, `Price Range`
   * Hover over map and charts for tooltip insights
5. Explore different visuals for comprehensive analysis

---

## 🏁 **Results & Conclusion**

The Airbnb dashboard delivers:

* Visual clarity on listing hotspots and competitive pricing zones
* Insightful breakdown of room types and booking behavior
* Actionable data to guide pricing strategies and investment locations

This Power BI dashboard empowers users to interactively explore Airbnb market data and supports smarter decision-making in the short-term rental space.
