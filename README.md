# MSc-Thesis
On Going Project - Exploring climate change impacts on renewable energy production. Working on  AI/ML models to predict output, optimize grids, and reduce penalties, alongside business analysis to improve efficiency and sustainability.
### Project Overview:
This ongoing project focuses on enhancing the accuracy of renewable energy forecasts, particularly for wind and solar energy production in coastal regions of France, where climate variability is most pronounced. The goal is to optimize weather predictions in order to improve grid stability, mitigate financial risks, and ensure the operational efficiency of renewable energy systems. By leveraging advanced forecasting techniques and analyzing both weather and energy production data, the project seeks to address the challenges of intermittent renewable energy sources while supporting France's transition to a sustainable, low-carbon energy future.

### Problem Statement:
The transition to renewable energy in France, particularly from wind and solar sources, has increased significantly in recent years. However, the intermittent nature of these sources poses substantial challenges to grid stability, operational efficiency, and financial sustainability for energy providers. As renewable energy production is highly weather-dependent, accurate forecasting is essential to balance supply and demand. Inaccurate predictions can lead to financial penalties, underproduction or overproduction of energy, and grid imbalances, which may increase the reliance on fossil fuels or imports, undermining the environmental benefits of renewable energy.

### Tools and Libraries Used:
1. **Weather Forecasting Tools**:
   - Météo-France and ECMWF: For gathering historical and forecasted weather data, including wind speed, solar radiation, temperature, and precipitation.
   - Python Libraries (e.g., Pandas, NumPy, Matplotlib): For data processing, visualization, and analysis.
   
2. **Energy Production Tools**:
   - RTE Data APIs: For retrieving historical data on energy production and consumption, focusing on renewable sources like wind and solar.
   - EPEX SPOT Market Data: For analyzing market prices, trading data, and financial implications related to energy transactions.

3. **Forecasting Models**:
   - Numerical Weather Prediction (NWP) Models: Used for short-term weather forecasts (30 minutes to 72 hours).
   - Ensemble Forecasting Techniques: To reduce uncertainty in wind and solar energy forecasts.

4. **Statistical and Financial Analysis Tools**:
   - SciPy: For conducting statistical analysis and scenario modeling.
   - Risk Analysis Tools: For assessing the financial impact of forecast errors and operational risks.
   - Monte Carlo Simulations: For running scenario-based analyses and understanding the impact of climate extremes on energy production.

### Dataset Description:
The datasets for this project include:
1. **Weather Data**:  
   - Historical and forecasted data on meteorological variables (wind speed, solar radiation, temperature, precipitation) for the coastal regions of France, sourced from Météo-France and ECMWF.
   
2. **Energy Production Data**:  
   - Data on wind and solar energy production from Réseau de Transport d'Électricité (RTE) for the past several years, detailing the generation patterns and forecast accuracy.

3. **Market Data**:  
   - Price fluctuations and trading volumes for energy on the EPEX SPOT platform, including financial incentives, subsidies, penalties, and pricing models that influence renewable energy markets.

### Steps Undertaken:
1. **Data Collection**:  
   Gather weather and energy production data, ensuring that variables like wind speed, solar radiation, and temperature are captured for the specified time periods. Energy production data is sourced from the RTE database, and market data from EPEX SPOT.

2. **Data Preprocessing**:  
   Clean and preprocess the datasets by handling missing values, outliers, and converting data into formats suitable for analysis and model training. This includes normalizing weather variables and aligning the timestamps between weather forecasts and energy production data.

3. **Model Development**:  
   - Implement forecasting models such as ensemble forecasting and numerical weather prediction models to predict wind and solar energy generation.
   - Evaluate the performance of these models by comparing forecast accuracy against actual energy production data.

4. **Financial and Risk Analysis**:  
   Analyze the financial implications of forecast errors, including penalties, operational costs, and revenue optimization strategies. Use sensitivity analysis to understand how changes in weather conditions impact financial outcomes.

5. **Scenario Testing**:  
   Simulate different weather scenarios, such as heatwaves or storms, to assess how forecast accuracy can help mitigate the financial risks of extreme events. The model will also consider future climate shifts and how to adapt forecasting methods.

6. **Results Evaluation**:  
   Evaluate the effectiveness of improved forecasting techniques in reducing operational costs, minimizing financial penalties, and optimizing energy trading strategies. Compare the outcomes with the current state of forecasting in the industry.

### Other Considerations:
- **Regulatory Framework**: Consideration of France's energy regulations, including the role of Balance Responsible Parties (BRPs), subsidies, and the European Clean Energy framework.
- **Impact of Climate Change**: The long-term impacts of climate change on weather patterns, particularly in coastal regions, and how forecasting models must evolve to remain accurate in the face of these changes.
- **Stakeholder Involvement**: The project will involve collaboration with renewable energy producers, grid operators, and financial analysts to ensure the practical relevance and applicability of the forecasting methods.

### Insights and Expected Outcomes:
Through this project, several key insights are expected:
1. **Improved Grid Stability**: Enhanced forecasting accuracy will contribute to better alignment between supply and demand, improving overall grid stability and reducing reliance on fossil fuels.
   
2. **Operational Efficiency**: Energy companies will benefit from optimized production strategies, reducing the need for reserve power and minimizing operational costs. Accurate forecasts will allow for better management of wind and solar resources.

3. **Financial Optimization**: By reducing forecast errors, renewable energy producers can avoid penalties and make more informed decisions regarding energy trading, pricing, and market participation. This will lead to increased profitability.

4. **Risk Mitigation**: The project will provide tools for energy producers to better manage financial risks, particularly during extreme weather events, and adjust their strategies accordingly.

5. **Contribution to Sustainability Goals**: The ability to integrate renewable energy more effectively into the grid will support France's transition to a more sustainable, low-carbon energy system. The project will contribute to both economic viability and environmental responsibility, aligning with national sustainability objectives.

In conclusion, this project aims to offer actionable insights and practical forecasting solutions to improve the stability and profitability of renewable energy systems in coastal France, helping energy producers mitigate financial risks and enhance their ability to meet energy demands amidst climate-induced variability.
