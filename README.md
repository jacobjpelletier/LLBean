# LL Bean Case Study: Item Forecasting and Inventory Management

## Overview
This repository contains an analysis of L.L. Bean's **item forecasting and inventory management** challenges, as explored in the Harvard Business School case study. The study investigates the difficulties of matching supply to demand, the implications of forecasting errors, and recommendations for improving inventory decisions.

## Objectives
The primary goals of this case study are:
1. Evaluate L.L. Bean's current forecasting and inventory processes.
2. Analyze the impact of **forecasting errors** on financial performance.
3. Propose actionable recommendations to optimize inventory management.
4. Understand the unique challenges of a catalog business model compared to retail.

## Key Takeaways
### Challenges
- **Forecasting Accuracy**: Variability in A/F (Actual/Forecast) ratios, with a mean of 1.02 and a standard deviation of 0.34, reveals significant variability across products.
- **One-Shot Commitments**: Long vendor lead times prevent mid-season adjustments, making accurate forecasts critical.
- **Understocking vs. Overstocking**: Annual costs of lost sales ($11M) and excess inventory ($10M) highlight the financial risks of mismatched supply and demand.

### Recommendations
1. **Enhanced Segmentation**:
   - Move beyond "New" vs. "Never Out" categories.
   - Implement detailed segmentation by product type (e.g., men's shirts, women's shoes) for more accurate demand forecasting.
   
2. **Dynamic Demand Adjustments**:
   - Improve vendor relationships to enable faster response times and in-season order adjustments.
   - Utilize real-time demand tracking for incremental forecasting updates.

3. **Probability-Based Forecasting**:
   - Use demand distributions to estimate a range of outcomes instead of relying on point estimates.
   - Balance the critical ratio (understocking vs. overstocking costs) to optimize order quantities.

4. **Refined Forecasting Models**:
   - Incorporate external factors like competition, economy, and customer behavior into forecasting models.
   - Leverage historical data to develop predictive analytics tools.

## Key Calculations
### Critical Ratio
- **Underage Cost (Cu)**: $20 (Selling price - Cost)
- **Overage Cost (Co)**: $10 (Cost - Liquidation value)
- **Critical Ratio Formula**: \( F(Q) = \frac{Cu}{Cu + Co} = 0.667 \)

### Order Quantity Adjustments
- For a fractile of **0.75**:
  - \( Q = \mu + z \times \sigma \)
  - Mean (\( \mu \)): 1.088, Standard Deviation (\( \sigma \)): 0.355
  - Calculated Quantity: 15,948 units
- For a fractile of **0.667**:
  - Calculated Quantity: 14,928 units
  - Savings achieved by ordering less using the critical ratio.

## Data Visualization
- A/F Ratios: Charted to illustrate demand variability across 71 products.
- Probability Distributions: Used to optimize inventory decisions for high-risk items.

## Insights into the Catalog Business Model
- **Analytical Nature**: Heavy reliance on quantitative demand forecasting.
- **Data-Driven Decisions**: Order commitments based on historical demand patterns.
- **Lead Time Challenges**: Limited flexibility compared to the retail business.

## Tools and Techniques
- **Statistical Analysis**: Mean, standard deviation, and z-scores for demand forecasting.
- **Segmentation**: Proposed improved grouping of items to refine forecasting accuracy.
- **Real-Time Monitoring**: Suggested incorporation of real-time data adjustments.

## Future Work
- Explore advanced machine learning techniques for demand prediction.
- Develop vendor partnerships for greater agility in inventory management.
- Enhance systems for integrating external demand influencers into forecasts.

## Authors
This analysis was conducted by **Group 6**:  
Adam Cohavi, Gil Delfino, Jacob Pelletier, Mike Milo, Nehal Lakdawala.

## License
This project is for educational purposes and adheres to the copyright policies of Harvard Business School. Contact the authors for further inquiries.
