# Inflation_Impact
# Inflation and Exchange Rate Analysis (2003–2024)

## Objective
This notebook analyzes the relationship between USD/INR exchange rates and inflation rates in India and the United States from 2003 to 2024. It tests the Purchasing Power Parity (PPP) theory by comparing actual exchange rates with expected rates based on inflation differentials. The analysis uses Python, Pandas, and Plotly to load, merge, visualize, and interpret economic data.

## Methodology
1. **Data Loading**: Import inflation and exchange rate datasets.
2. **Data Preparation**: Merge datasets, focusing on India and US inflation rates and USD/INR exchange rates.
3. **Visualization**:
   - Subplots to show individual trends (exchange rate, India inflation, US inflation).
   - Combined chart with dual y-axes for comparative analysis.
   - Actual vs. expected exchange rate based on PPP.
   - Correlation heatmap to assess variable relationships.
4. **Analysis**: Interpret trends, PPP deviations, and correlations to draw economic insights.

## Tools
- **Python Libraries**: Pandas (data manipulation), Plotly (interactive visualizations).
  
## Conclusion
- **Key Findings**:
  - INR depreciated significantly (45.48 to 83.31 INR/USD), but less than PPP predicts (97.69 INR/USD).
  - India’s inflation stabilized post-2016; US inflation was more volatile.
  - Weak correlations indicate other factors drive exchange rates.
