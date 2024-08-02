
# A/B Testing Analysis: Marketing Campaign Comparison

## Project Overview

This project conducts a comprehensive A/B testing analysis to compare two marketing campaigns: Control Campaign and Test Campaign. The objective is to identify the most effective marketing strategy by analyzing various metrics such as impressions, website clicks, content views, add-to-cart actions, and purchases.

### What Was Done

- **Data Cleaning and Preprocessing**: Handled missing values, standardized formats, and prepared the datasets for analysis.
- **Exploratory Data Analysis (EDA)**: Investigated patterns in campaign performance across various metrics.
- **Statistical Analysis**: Compared key performance indicators between the Control and Test campaigns.
- **Data Visualization**: Created various charts and graphs to illustrate campaign performance differences.
- **Conversion Funnel Analysis**: Examined the effectiveness of each campaign at different stages of the customer journey.

### Key Findings

- The Control Campaign generated more impressions per amount spent compared to the Test Campaign.
- The Test Campaign resulted in more website clicks and searches.
- The Control Campaign had higher engagement in terms of content views per click.
- The Test Campaign showed a higher conversion rate from add-to-cart to purchases.
- Overall, the Control Campaign resulted in slightly more purchases, but the Test Campaign was more efficient in some conversion metrics.

## Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization (Plotly)
- Statistical Analysis
- A/B Testing Methodology
- Python Programming
- Jupyter Notebook

## Dataset

### Description

The dataset contains information about two marketing campaigns: Control Campaign and Test Campaign. It includes daily metrics for each campaign over a period of time.

### Key Attributes

| Attribute Name | Description | Data Type | Example Value |
|----------------|-------------|-----------|---------------|
| Campaign Name | Name of the campaign | String | Control Campaign |
| Date | Date of the campaign | Date | 1.08.2019 |
| Amount Spent | Amount spent on the campaign (in USD) | Float | 2280.0 |
| Number of Impressions | Number of impressions | Float | 82702.0 |
| Reach | Reach of the campaign | Float | 56930.0 |
| Website Clicks | Number of website clicks | Float | 7016.0 |
| Searches Received | Number of searches | Float | 2290.0 |
| Content Viewed | Number of content views | Float | 2159.0 |
| Added to Cart | Number of add-to-cart actions | Float | 1819.0 |
| Purchases | Number of purchases | Float | 618.0 |

## Visualizations

### 1. Campaign Performance Overview

<div align="center">
<img width="800" alt="Campaign Performance Overview" src="https://github.com/user-attachments/assets/9165b144-6421-4a1e-b282-7e5eb4b6a5dd">
<p><strong>Comparison of Key Metrics Between Control and Test Campaigns</strong></p>
</div>

#### Description:
This image contains six pie charts comparing various metrics between the Control and Test campaigns:

1. **Purchases**: The Control Campaign (51.7%) slightly outperformed the Test Campaign (48.3%) in total purchases.
2. **Added to Cart**: The Test Campaign (59.8%) had more add-to-cart actions compared to the Control Campaign (40.2%).
3. **Amount Spent**: The Test Campaign (52.8%) spent slightly more than the Control Campaign (47.2%).
4. **Searches**: The Test Campaign (52.2%) generated more searches than the Control Campaign (47.8%).
5. **Website Clicks**: The Test Campaign (53.2%) received more website clicks than the Control Campaign (46.8%).
6. **Content Viewed**: The Control Campaign (51.1%) had slightly more content views than the Test Campaign (48.9%).

These charts provide a quick overview of how each campaign performed across different stages of the customer journey.

### 2. Relationship Analysis

<div align="center">
<img width="800" alt="Relationship Analysis" src="https://github.com/user-attachments/assets/7d0cf451-30c3-43c6-b4f8-ad1d482afba8">
<p><strong>Scatter Plots Analyzing Relationships Between Different Metrics</strong></p>
</div>

#### Description:
This image contains four scatter plots analyzing relationships between different metrics for both campaigns:

1. **Purchases vs. Added to Cart**: Shows a positive correlation between items added to cart and purchases for both campaigns, with the Test Campaign having a steeper trend line.
2. **Content Viewed vs. Added to Cart**: Illustrates the relationship between content views and add-to-cart actions, with the Test Campaign showing a slightly higher trend.
3. **Website Clicks vs. Content Viewed**: Demonstrates how website clicks relate to content views, with the Control Campaign showing a steeper increase.
4. **Amount Spent vs. Number of Impressions**: Compares the efficiency of spend in generating impressions, with the Control Campaign showing better performance.

These plots help in understanding the effectiveness of each campaign at different stages of the customer journey and the efficiency of spend.

## Conclusion

The A/B testing analysis revealed strengths and weaknesses in both campaigns:

1. The Control Campaign was more efficient in generating impressions and engaging users with content.
2. The Test Campaign was more effective in driving website clicks and searches.
3. While the Control Campaign led to slightly more overall purchases, the Test Campaign showed a higher conversion rate from add-to-cart to purchase.

A hybrid approach leveraging the strengths of both campaigns could be most effective for future marketing efforts.

## How to Use

To explore and utilize this project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/crishN144/AB_Testing_Analysis.git
   cd AB_Testing_Analysis
   ```

2. **Set Up the Environment**:
   - It's recommended to use a virtual environment:
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows use `venv\Scripts\activate`
     ```
   - Install required dependencies:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Analysis**:
   - Open Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Navigate to and open `Marketing_Campaign_Comparison.ipynb`
   - Run the cells sequentially to reproduce the analysis

4. **Explore the Results**:
   - Examine the visualizations and insights generated in the notebook
   - Modify parameters or add new analyses as needed

## Future Work

To further enhance this project, the following future works are proposed:

1. **Time Series Analysis**: Analyze how campaign performance changes over time to identify trends or seasonality.
2. **Customer Segmentation**: Investigate if certain customer segments respond differently to each campaign.
3. **Cost-Benefit Analysis**: Conduct a detailed analysis of the return on investment for each campaign.
4. **Multi-variate Testing**: Expand the analysis to test multiple variables simultaneously in future campaigns.
5. **Machine Learning Models**: Develop predictive models to forecast campaign performance based on various input parameters.

