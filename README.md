# PGA Tour Performance Analysis

### [📊 View Full Project (HTML)](https://htmlpreview.github.io/?https://raw.githubusercontent.com/BradyTokarski/PGA-Tour-Performance-Analysis/main/PGA_Tour_Analysis.html)


## Project Overview
This project analyzes 2025 PGA Tour player statistics to investigate whether longer driving distance is associated with better scoring performance, more top-10 finishes, and higher earnings. Data was collected from ESPN using Python web scraping and examined through data visualization, descriptive statistics, and hypothesis testing.

## Tools & Technologies
- Python
- Pandas
- BeautifulSoup and Requests (web scraping)
- Matplotlib, Seaborn, and Plotly (visualization)
- SciPy (statistical testing)
- Jupyter Notebook

## Data Source
ESPN PGA Tour player statistics, including driving distance, scoring average, greens in regulation (GIR), total earnings, and top-10 finishes. The analysis focuses on a sample of 50 PGA Tour golfers.

## Analysis
1. **Driving Distance vs. Scoring Average:** Created a scatter plot to explore the relationship between driving distance and scoring performance.
2. **Top-10 Finishes by Driving Distance:** Grouped golfers into short, medium, and long hitters to compare combined top-10 finishes.
3. **Greens in Regulation vs. Scoring:** Used boxplots to compare scoring distributions across GIR groups.
4. **Earnings by Driving Distance:** Visualized the proportion of total earnings across driving-distance groups.
5. **Descriptive Statistics:** Summarized player performance metrics and variability.
6. **Hypothesis Testing:** Conducted a Welch two-sample t-test comparing scoring averages of long and short hitters.

## Key Findings
- Longer hitters collectively recorded more top-10 finishes and the largest share of earnings in the analyzed sample.
- Golfers with higher greens-in-regulation percentages generally achieved lower scoring averages.
- The driving-distance t-test produced a p-value of 0.146, indicating no statistically significant difference in scoring averages between long and short hitters at the 0.05 significance level.
- Driving distance may offer advantages, but scoring performance depends on multiple factors.

## How to View the Project
Open `DAT301_FINAL_PROJECT.ipynb` in this repository to review the code, visualizations, and analysis. The notebook retrieves data from ESPN, so rerunning it requires internet access, and changes to ESPN's page structure may affect the scraping code.
