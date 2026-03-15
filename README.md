# Boston Airbnb Strategic Analytics (Python)

## 📌 Project Overview
This project analyzes 4,419 Airbnb listings in Boston to uncover the key drivers of price, revenue, occupancy, and guest experience. Using Python and statistical modeling, the analysis identifies which listing features matter most for host success — and where hosts lose value through poor configuration, calendar mismanagement, or guest experience gaps.

This work was completed for ISOM 835 under Prof. Hasan Arslan and was later recognized for its analytical depth and clarity.

---

## 📂 Dataset
The dataset (`Listings.csv`) is not included in this repository because it is sourced externally from Inside Airbnb.  
Users can download the public dataset from: https://insideairbnb.com/get-the-data/  
Place the file in the project root before running the notebook.

---

## 🔧 Data Preprocessing
The original dataset contained **79 columns** and was reduced to **53** after removing irrelevant or redundant fields.  
Several new engineered features were created to enhance analytical depth:

- `price_per_person`  
- `occupancy_vs_availability`  
- `revenue_per_day`  
- `host_tenure_years`  

Additional preprocessing steps included:

- Converting categorical variables (e.g., neighborhood, response time) into numeric form  
- Cleaning missing values  
- Standardizing date formats  
- Computing host tenure using `host_since` and `last_scraped`  

---

## 📊 Analysis & Visualizations
This project includes a series of visualizations and statistical analyses to uncover patterns in:

- Pricing behavior across neighborhoods  
- Revenue performance  
- Occupancy vs. availability  
- Guest experience indicators  
- Feature importance for price, revenue, and occupancy  

All visualizations are available in the `images/` folder and embedded within the notebook.

---

## 🧠 Key Insights
Some of the major findings include:

- **Neighborhood matters** — areas like Bay Village and Longwood Medical Area show significantly higher revenue per day.  
- **Host tenure influences performance** — experienced hosts tend to price more effectively and maintain higher occupancy.  
- **Price per person is a strong predictor** of both revenue and guest satisfaction.  
- **Availability patterns reveal inefficiencies** — many hosts lose revenue due to poor calendar management.  

(You may expand this section with more insights from your notebook.)

---

## ▶️ How to Run the Notebook
1. Download `Listings.csv` from Inside Airbnb  
2. Place it in the project root (same folder as the notebook)  
3. Open the notebook in **Google Colab**, **Jupyter Notebook**, or **VS Code**  
4. Run all cells to reproduce the analysis  

---

## 📁 Repository Structure
