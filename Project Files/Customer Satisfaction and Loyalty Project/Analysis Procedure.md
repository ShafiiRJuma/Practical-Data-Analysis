# OMNIRETAIL CUSTOMER SATISFACTION AND LOYALTY ANALYSIS

**Organization:** Onyx Data  
**Dataset:** Omni Retail Customer satisfaction and loyalty dataset.  
**Tool:** Power BI  
**Data Analyst:** Shafii R Juma  
**Date:** July 2025  
**Goal:** Prepare an analytical report that identifies the key factors influencing customer satisfaction and loyalty across different regions, customer demographics, and support experience.

## Introduction:
Omni Retail is a US-based retail chain selling electronics and smart home products both online and through physical stores. In an effort to increase customer satisfaction and retention, the company collected customer experience data throughout 2024. The dataset includes satisfaction scores, purchasing behavior, demographics, support history, and geographic location.

## Key Business Questions:
- What are the main factors contributing to high vs. low satisfaction scores?
- Are certain customer segments (by age, gender, or group) more loyal than others?
- Which locations report consistently high or low satisfaction scores?
- Does contacting customer support negatively impact satisfaction?
- How do factors like Price or Product Variety influence customer loyalty?
- Do repeat purchasers report higher satisfaction?
- Are there regional clusters of loyal or dissatisfied customers?
- What is the relationship between loyalty level and satisfaction score?
- Do specific demographic groups favor certain satisfaction factors?


## Data Dictionary (Key Columns):

| Column Name         | Description                                                           |
|---------------------|-----------------------------------------------------------------------|
| Customer_ID         | Unique customer identifier                                            |
| Group               | Customer frequency classification: A (high), B (moderate), C (low/new)|
| Satisfaction_Score  | Score from 1 (very poor) to 10 (excellent)                            |
| Age and Gender      | Demographic attributes                                                |
| Location            | City and State (e.g., Austin.TX), with lat-long                       |
| Purchase_History    | Indicates whether the customer has purchased (Yes/No)                 |
| Support_Contacted   | Whether customer interacted with support                              |
| Loyalty_Level       | Internal rating: Low, Medium, or High loyalty                         |
| Satisfaction_Factor | Main reason influencing satisfaction score                            |


## Methodology:
1. I started by creating a backup copy of the dataset to ensure I could get back to the original if needed.  
2. The dataset contained 121 rows and 12 columns.  
3. I checked for duplicates both generally and on Customer_ID and no duplicates were found.  
4. I reviewed all column data types and formatting. Everything was consistent and clean.  
5. I confirmed the dataset was ready for analysis without needing major cleaning.  
6. Using Pivot Tables, I explored the data to uncover initial insights:  
   a. The average customer age was 43 years  
   b. The average satisfaction score was 5.35  
   c. Age range spanned from 25 to 60  

7. I added a new column called Age Group to simplify demographic analysis:  
   a. Young Adults: Age 25–29  
   b. Settlers: Age 30–39  
   c. Mature Professionals: Age 40–49  
   d. Pre-Retirees: Age 50–60  

8. I also created a Satisfaction Category column for group satisfaction scores:  
   a. Satisfied: Score 7–10  
   b. Neutral: Score 4–6  
   c. Unsatisfied: Score 1–3  

9. After these changes, the dataset had 14 columns.


## Visualization and Analysis Summary:

1. **Key Question: Are customers really satisfied?**  
   To answer this, I used a pie chart to see the percentage of customers in each satisfaction category (Satisfied, Neutral, Unsatisfied). I found that only 36.7% of customers are satisfied. This highlights an urgent need to improve the overall experience for a majority of customers.

2. **Key Question: Does customer support affect satisfaction?**  
   I used a 100% stacked bar chart comparing satisfaction levels between customers who contacted support and those who didn’t. The result showed that customers who contacted support were more likely to be dissatisfied, suggesting that the support experience may be a major pain point.

3. **Key Question: Which satisfaction factors are most influential?**  
   To explore this, I used a 100% stacked bar chart by satisfaction factor. The data showed that packaging (67%) and product quality (64%) had the highest satisfaction levels, while ease of use, price, and support availability were major contributors to dissatisfaction. These signals where improvements should be prioritized.

4. **Key Question: Does frequency of purchase affect satisfaction?**  
   Using a simple table, I compared satisfaction categories by customer group (A, B, C). I noticed that Group B (moderate-frequency shoppers) appear across all satisfaction levels, indicating mixed experiences and a strong opportunity to improve satisfaction within this important segment.

5. **Key Question: Are certain age groups more loyal than others?**  
   I used a 100% stacked area chart to compare loyalty levels by age group. The result was clear: Young Adults (25–29) had the highest loyalty (46%), while Adults (30–39) and Pre-Retirees (50–60) showed the highest levels of disloyalty. This shows loyalty tends to decline with age.

6. **Key Question: Does customer support affect loyalty?**  
   To answer this, I used a stacked column chart comparing loyalty levels between customers who did and didn’t contact support. The analysis showed a drop in loyalty among customers who contacted support, reinforcing that the support experience may not be meeting expectations.

7. **Key Question: Which satisfaction factors drive loyalty?**  
   I used a 100% stacked bar chart to analyze how satisfaction factors relate to loyalty levels. Ease of use (50%) and customer service (45%) stood out as top loyalty drivers. In contrast, features (58%), product quality (55%), and variety (50%) were most cited among customers with low loyalty.

8. **Key Question: Does loyalty mean a customer is satisfied?**  
   Here I used a table to compare satisfaction categories across different loyalty levels. The insight was surprising only 38% of highly loyal customers are satisfied, while 44% of low-loyalty customers are actually satisfied. This means satisfaction doesn’t automatically translate to loyalty.

9. **Key Question: Does satisfaction vary by location?**  
   I used a bar chart to show average satisfaction score per city. Cities like Chicago (6.36), Austin (6.35), and New York (6.0) scored above the overall average of 5.3. In contrast, Dallas (4.89), Los Angeles (4.86), and San Antonio (3.5) fell well below average, signaling a need for improvement in those areas.

10. **Key Question: Does loyalty vary by location?**  
    I created a 100% stacked bar chart to compare loyalty levels across cities. New York led with 56% high loyalty, and Chicago and Los Angeles both showed 50%. On the other hand, Austin (50%), Dallas (56%), and Phoenix (58%) showed high levels of disloyalty even though Austin had high satisfaction. This highlights that loyalty and satisfaction don’t always align.

11. **Key Question: Are female customers more loyal than males?**  
    Using a 100% stacked bar chart, I compared loyalty levels by gender. Male customers were more loyal (37%) and less disloyal (33%), while females were more likely to disengage (41% less loyal, only 26% highly loyal). This highlights the need to address potential experience gaps for female customers.

12. **Key Question: What satisfaction factors matter most to female customers?**  
    To understand what drives satisfaction for women, I used a horizontal bar chart showing the percentage of female customers selecting each factor. Brand reputation (18%), ease of use (15%), and packaging (14%) ranked highest, while features, support availability, and price were least mentioned. This shows that women value brand image and experience over technical features.


## Conclusion:
My analysis reveals that satisfaction and loyalty are driven by different factors. While product quality and packaging generate satisfaction, they don’t necessarily create loyalty. Experience-focused elements like ease of use, customer support, and brand perception are more influential when it comes to retaining customers.  

To improve both satisfaction and loyalty, Omni Retail should focus on:
- Enhancing the support experience  
- Simplifying the product usage  
- Improving product variety and feature performance  
- Tailoring retention strategies for specific age and gender segments  

Addressing these areas will help turn satisfied users into loyal customers and reduce churn in critical segments and regions.
