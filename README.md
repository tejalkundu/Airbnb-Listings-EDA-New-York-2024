# 🏙️ Airbnb Listings EDA – New York 2024

## 📌 Overview

This project conducts **Exploratory Data Analysis (EDA)** of Airbnb listings in **New York City** to uncover patterns in pricing, room types, availability, and host behaviors. By leveraging Python libraries such as `Pandas`, `NumPy`, `Matplotlib`, and `Seaborn`, we draw meaningful insights to inform guests and hosts alike.

---

## 🎯 Objectives

- Analyze room types, pricing, and availability across NYC boroughs  
- Understand host behavior and multi-listing trends  
- Identify pricing outliers and anomalies  
- Provide data-backed recommendations for Airbnb users

---

## 🗂️ Dataset Description

The dataset includes **20,765 entries** and **22 features** related to Airbnb listings in NYC.

**Key Features:**
- `id`: Unique listing ID  
- `name`: Title of the listing  
- `host_name`: Host’s name  
- `neighbourhood_group`: Borough (e.g., Manhattan, Brooklyn)  
- `latitude`, `longitude`: Geolocation  
- `room_type`: Entire home, private room, etc.  
- `price`: Per night cost  
- `reviews_per_month`: Avg. monthly reviews  
- `availability_365`: Days available per year  

---

## 🧪 Workflow Summary

### 1️⃣ Data Cleaning
- Handled null values in `price`, `neighbourhood`, `beds`
- Converted `last_review` to datetime format
- Removed extreme outliers (`price > $1,000` capped)

### 2️⃣ Exploratory Data Analysis (EDA)

#### 🏠 Room Types
- Majority listings are *Entire homes/apartments*
- Bar plots show distribution by room type

#### 📍 Neighborhoods
- Manhattan has the highest prices on average  
- Price and availability trends vary by borough

#### 📊 Price Distribution
- Most listings priced between **$50–$300**
- Histograms and boxplots used for visualization  
- Listings above $10,000 flagged as outliers

#### 📅 Availability
- Listings with higher availability tend to have more reviews and lower prices  
- Heatmaps reveal correlations among `price`, `availability`, and `reviews`

#### 👤 Host Analysis
- Some hosts
- Some hosts manage 5+ listings — professional hosting observed  
- Boxplots used to highlight pricing patterns among multi-listing hosts

#### 📝 Review Trends
- Pairplots explored relationships between reviews, price, and availability

---

## 📈 Visualizations Used

- **Histograms & Boxplots** – Price distribution & outliers  
- **Bar Charts** – Room types and borough comparison  
- **Heatmaps** – Correlation among numerical variables  
- **Pairplots** – Multivariable relationships  
- **Geospatial plots** *(optional for future expansion)*

---

## 🔍 Key Insights

- **Room Types**: Entire homes dominate listings; private rooms are more affordable  
- **Manhattan Listings**: Most expensive on average  
- **Outliers**: Few listings priced at $10,000+  
- **High Availability**: Correlates with positive reviews & affordability  
- **Professional Hosts**: Manage multiple listings

---

## 🛠️ How to Run

1. Clone this repository  

2. Install dependencies  
```bash
pip install pandas numpy matplotlib seaborn
```

3. Launch the Jupyter Notebook  


---

## 💡 Recommendations

### For Guests
- Prioritize listings with **high availability** and **strong reviews**
- Choose **private rooms** in Brooklyn for budget-friendly stays

### For Hosts
- Maintain high availability to boost visibility  
- Strategically price listings to remain competitive in boroughs  
- Focus on guest experience to drive more reviews

---

## 🚀 Future Enhancements

- 🔮 Predict listing prices using machine learning  
- 💬 Perform **sentiment analysis** on user reviews  
- 📊 Develop an **interactive dashboard** using Plotly or Tableau

---

## 📚 Conclusion

Through EDA, this project reveals actionable insights into NYC’s Airbnb ecosystem—empowering hosts and guests to make better decisions. Future iterations can evolve into predictive analytics and live dashboards for real-time market monitoring.


