# 🏡 Airbnb Price Trends Analysis

This repository contains a comprehensive **data analysis project** that explores **Airbnb listings** in a specific city (e.g. **New York**, **San Francisco**, etc.). The goal is to discover **price patterns**, analyze **location-based trends**, and understand how **listing types, availability, and neighborhood** affect rental prices.



## 📑 Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Objectives](#objectives)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Analysis Overview](#analysis-overview)
* [Visualizations](#visualizations)
* [Key Insights](#key-insights)
* [Project Structure](#project-structure)
* [Future Work](#future-work)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



## 📝 Introduction

Airbnb has transformed the short-term rental industry, offering various options from shared rooms to luxury apartments. Understanding how **location, room type, and amenities** affect pricing can benefit both **hosts and guests**.

This project applies **exploratory data analysis (EDA)** and **visualization** techniques to uncover trends in Airbnb listings and provide insights into pricing behavior.



## 📂 Dataset

* **Source:** [Inside Airbnb]()
* **City:** e.g. New York City, San Francisco *(can be changed)*
* **Data Format:** CSV
* **Attributes Include:**

  * `price`, `room_type`, `neighbourhood`, `minimum_nights`, `number_of_reviews`, `availability_365`, `latitude`, `longitude`, etc.



## 🎯 Objectives

✅ Understand how listing type (entire home, shared room, private room) affects price

✅ Explore which neighborhoods have higher/lower average pricing

✅ Visualize geographic price distributions using maps

✅ Identify correlations between price and reviews, availability, or host behavior

✅ Detect outliers and clean the dataset for accurate insights



## ✨ Features

✔️ Load and preprocess Airbnb data (remove nulls, convert price format)

✔️ Create statistical summaries and group-by aggregations

✔️ Generate visualizations: bar charts, histograms, boxplots, heatmaps

✔️ Plot geospatial data to show price hotspots using scatter maps

✔️ Identify and filter outliers in pricing



## 🛠️ Technologies Used

* **Python 3**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Plotly** *(optional for interactive maps)*
* **GeoPandas / Folium** *(optional for geographic visualizations)*
* **Jupyter Notebook**



## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/Airbnb_Price_Trends_Analysis.git
cd Airbnb_Price_Trends_Analysis
```

2. **Create a virtual environment (optional)**

```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook**

```bash
jupyter notebook
```



## ▶️ Usage

1. Open the notebook `Airbnb_Price_Trends_Analysis.ipynb`
2. Run each cell to:

   * Load and clean the dataset
   * Analyze price trends
   * Visualize listing distributions
   * Discover geographic price patterns



## 📊 Analysis Overview

* **Room Type Analysis:** Average prices for Entire Home vs Shared Room
* **Neighborhood Breakdown:** Price distribution by region
* **Price vs Availability:** Seasonal and yearly trends
* **Price vs Review Count:** Does popularity impact pricing?
* **Geospatial Plotting:** Price clusters on a city map



## 📸 Visualizations

* 📌 Bar charts of average prices by neighborhood
* 📍 Heatmaps of price by room type and location
* 📈 Line plots of listings over time
* 🗺️ Geographic scatter plots of listings with color-coded pricing

> *(Screenshots coming soon)*



## 🔍 Key Insights

* 🏙️ Downtown and tourist-heavy neighborhoods tend to have higher average prices
* 🛌 Entire homes are priced significantly higher than private or shared rooms
* 📆 Listings with greater availability tend to be more competitively priced
* ⭐️ High review counts do not always equate to higher pricing



## 📁 Project Structure

```
Airbnb_Price_Trends_Analysis/
 ┣ data/
 ┃ ┗ airbnb_city_data.csv
 ┣ Airbnb_Price_Trends_Analysis.ipynb
 ┣ requirements.txt
 ┗ README.md
```



## 🚀 Future Work

* Add **machine learning model** to predict prices based on features
* Include **time-series forecasting** for dynamic pricing
* Build a **dashboard** using Streamlit or Plotly Dash
* Integrate **sentiment analysis** from review text



## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to your branch (`git push origin feature/YourFeature`)
5. Open a pull request



## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.



## 📬 Contact

**Ugama Benedicta Kelechi**
[LinkedIn](www.linkedin.com/in/ugama-benedicta-kelechi-codergirl-103041300) | [Email](mailto:ugamakelechi501@gmail.com) | [Portfolio](#)



### ⭐️ Found this project useful? Star it and share with other data science learners!

