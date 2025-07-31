# Marketing_campaigns_analysis
This project is a detailed **Exploratory Data Analysis (EDA)** of delivery marketing campaigns aimed at identifying underperforming or inactive campaigns and recommending data-driven strategies to **increase profitability**.  

We explore why some campaigns are inactive or not delivering, determine performance factors like frequency, impressions, and reach, and visualize patterns to guide better investment in high-performing campaigns.

---

## Project Goals

Marketing teams often face challenges optimizing digital campaigns due to data noise and unclear performance indicators.  
This analysis provides:

- Insights into why certain campaigns are inactive or not delivering
- Visual diagnostics of performance metrics
- Strategic recommendations based on EDA findings

---

## Project Structure

The project is structured into multiple tasks within a Jupyter notebook:

### Tasks Breakdown

1. **Problem Framing and Overview**
   - Understand the business challenge: improving ROI from digital campaigns.

2. **Importing Libraries & Dataset**
   - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `collections`
   - Dataset: `dummy data.csv`

3. **Data Cleaning**
   - Dropped irrelevant and Arabic-labeled columns
   - Handled missing values
   - Normalized data (e.g., converting Arabic text to English)

4. **Visual Analysis**
   - Scatter plots for `Amount Spent` vs `Results`
   - Correlation between `Frequency`, `CTR`, `Reach`, and `Cost per Result`

5. **Inactive Campaign Analysis**
   - Extracted top reasons: low reach, low CTR, high CPC, bad frequency
   - Visualized loss potential due to bad frequency and spending patterns

6. **Not Delivered Campaigns**
   - Similar root causes identified
   - Key difference: low reach is more significant than in inactive ones

7. **Optimization Insights**
   - Recommend increasing frequency control
   - Focus spending on campaigns with high reach and low cost per result
---

## Key Takeaways

- Campaigns with **bad frequency** are a major reason for inactivity or waste.
- **High reach + low cost per result** = good investment.
- Reallocate budget based on data, not assumptions.

---

## Tools Used

- **Python** (pandas, matplotlib, seaborn)
- **Jupyter Notebook**
- **Data Cleaning & Visualization**
- **Basic ML Preprocessing** (Label Encoding)
