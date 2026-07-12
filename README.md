# Supermarket Sales - Exploratory Data Analysis (EDA)

An intermediate-level exploratory data analysis project focused on understanding customer purchasing behaviors, storefront operational patterns, and product line performance using Python.

## 🎯 Project Objectives
* **Data Integrity Evaluation:** Check for missing data fields and correct structural inconsistencies in data types.
* **Categorical Aggregations:** Apply `groupby` operations to evaluate transaction distribution across branches, customer types, genders, and inventory lines.
* **Time-Series Insights:** Isolate hourly components to reveal daily customer traffic density patterns.
* **Statistical Visualizations:** Deploy matplotlib and seaborn to output trend tracking charts and correlation heatmaps.

## 🛠️ Tech Stack & Libraries
* **Python 3**
* **Jupyter Notebook** (Interactive Development Environment)
* **Pandas** (Data Manipulation & Groupby Aggregations)
* **Matplotlib** (Core Chart Architectures)
* **Seaborn** (Advanced Visual Aesthetics & Statistical Heatmaps)

## 📂 Repository Contents
* `supermarket_sales - Sheet1.csv`: The raw historical supermarket transaction record.
* `supermarket_eda.ipynb`: Complete code implementation including cleaning stages, mathematical groupings, and charts.
* `note.md`: Concise operational summary detailing pipeline data mutations and targeted business insights.

## 📊 Key Findings Highlight
1. **Double-Peak Traffic:** Store floor traffic peaks decisively around two distinct intervals—Lunch hour (**13:00**) and early evening (**19:00**).
2. **Product Performance Drivers:** The "Food and beverages" and "Sports and travel" classifications represent the highest overall profit streams.
3. **Branch & Cohort Equilibrium:** Data indicates a virtually identical distribution of total orders among structural store Branches (A, B, C) and customer statuses (Member vs. Normal).

## 🚀 How to Run the Project Local
1. Clone this repository to your machine.
2. Ensure you have python dependencies installed: `pip install pandas matplotlib seaborn`
3. Launch Jupyter Notebook and open `supermarket_eda.ipynb` to view or rerun the live computations.
