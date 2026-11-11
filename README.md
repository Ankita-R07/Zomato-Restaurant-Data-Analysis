# Zomato Restaurant Data Analysis

## Project Overview

This project focuses on analyzing restaurant data to understand restaurant types, customer ratings, pricing patterns, cuisine preferences, and the availability of online ordering and table booking services.

Using Python, the project applies data cleaning, exploratory data analysis (EDA), and data visualization to identify patterns and generate insights into restaurant performance and customer preferences.

## Objectives

- Analyze the distribution of different restaurant types.
- Understand customer rating patterns and restaurant performance.
- Examine average dining costs across restaurant categories.
- Explore online ordering and table booking availability.
- Identify areas with a higher concentration of highly rated restaurants.
- Understand the relationship between restaurant services, ratings, and average costs.

## Dataset Description

The project uses the `Zomato_DS.csv` dataset containing restaurant information.

**Dataset Overview:**
- Total Records: 7,105 restaurants
- Original Columns: 12
- Columns Retained for Analysis: 8
- Missing Values: Present in restaurant ratings and average cost.

**Key Features:**

| Column | Description |
|---|---|
| Restaurant Type | Category of restaurant |
| Rate (out of 5) | Customer rating |
| Number of Ratings | Total customer ratings |
| Average Cost (Two People) | Estimated dining cost for two people |
| Online Order | Online ordering availability |
| Table Booking | Table reservation availability |
| Cuisines Type | Cuisine categories offered |
| Area | Restaurant location |

## Technologies & Libraries Used

- **Python:** Primary programming language
- **Pandas:** Data manipulation and analysis
- **NumPy:** Numerical operations
- **Matplotlib:** Data visualization
- **Seaborn:** Statistical data visualization
- **Jupyter Notebook:** Development environment

## Project Workflow

### 1. Data Loading & Exploration
- Imported the dataset using Pandas.
- Examined the first few records and dataset structure.
- Checked column names, data types, and dataset information.

### 2. Data Cleaning & Preprocessing
- Removed unnecessary columns, including duplicate index columns, restaurant names, and local addresses.
- Identified missing values in restaurant ratings and average dining costs.
- Handled missing ratings using mean imputation.
- Handled missing average costs using median imputation.
- Converted online ordering and table booking values into binary format for analysis.

### 3. Exploratory Data Analysis (EDA)

Performed analysis using 10 business-oriented questions:

1. What are the most common restaurant types in the dataset?
2. What is the overall distribution of ratings across restaurants?
3. How do restaurant ratings vary across different restaurant types?
4. What is the average cost for two people across different restaurant types?
5. How does the availability of online ordering and table booking vary across restaurant types?
6. Which areas have the highest concentration of highly rated restaurants?
7. Which cuisines are most commonly associated with highly rated restaurants?
8. How does the availability of online ordering and table booking relate to customer ratings?
9. How does online ordering availability relate to average ratings and dining costs?
10. Do restaurants offering table booking have different average ratings and costs compared to those that do not?

### 4. Data Visualization

Used different visualization techniques to understand and present the findings:

- Bar Charts
- Histograms
- Pie Charts
- Comparative Bar Plots
- Distribution Plots

## Key Findings & Business Insights

The analysis revealed several interesting patterns:

**1. Restaurant Type Distribution**
- Quick Bites is the most common restaurant category, with 2,840 records.
- Casual Dining follows with 1,634 records.

**2. Customer Ratings**
- The average restaurant rating is approximately 3.51 out of 5.
- Most restaurant ratings are concentrated around the 3.0–4.0 range.

**3. Restaurant Pricing**
- The overall average dining cost for two people is approximately ₹539.16.
- The median dining cost is ₹400.

**4. Online Ordering & Table Booking**
- Approximately 52.5% of restaurants offer online ordering.
- Only 10.5% offer table booking facilities.
- Online ordering is more widely available than table booking.

**5. Location-Based Analysis**
- Byresandra, Tavarekere, and Madiwala have the highest number of highly rated restaurants in the area-wise analysis (rating above 4.0).

**6. Cuisine Preferences**
- Cuisines such as South Indian, Cafe, Beverages, North Indian, Continental, and American frequently appear among highly rated restaurants (rating of 4.5 or above).

**7. Online Ordering Comparison**
- Restaurants offering online ordering have an average rating of approximately 3.55, compared to 3.47 for those without it.
- Their average dining cost is approximately ₹488, compared to ₹596 for restaurants without online ordering.

**8. Table Booking Comparison**
- Restaurants offering table booking have an average rating of approximately 4.04, compared to 3.45 for those without it.
- Their average dining cost is approximately ₹1,355, compared to ₹444 for restaurants without table booking.

*Note: These findings show associations and differences in the dataset; they do not establish that service availability directly causes changes in ratings or costs.*

## Repository Structure

```text
Zomato-Restaurant-Data-Analysis/
│
├── Zomato Data Analysis Code.ipynb
├── Zomato_DS.csv
└── README.md
```

## How to Run the Project

1. Clone the repository:

```bash
git clone <your-repository-url>
```

2. Navigate to the project directory:

```bash
cd Zomato-Restaurant-Data-Analysis
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Ensure `Zomato_DS.csv` is available in the notebook's working directory.

5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `Zomato Data Analysis Code.ipynb` and run the cells to explore the analysis and visualizations.

## Conclusion

This project provided practical experience in data cleaning, exploratory data analysis, statistical summaries, and visualization using Python. The analysis helped identify restaurant distribution patterns, customer rating trends, pricing differences, and service availability across different restaurant categories and locations.

It demonstrates how exploratory data analysis can be used to understand business data and generate meaningful insights to support informed decision-making.
