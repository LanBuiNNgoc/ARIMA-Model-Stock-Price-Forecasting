# ARIMA-Model-Stock-Price-Forecasting
## Project Background
This is the project that me - together with the Investment Club at the University of South Florida used to promote the school organization in the IMC Hedge Fund Competition.
<br/>The oil market is essential to the global economy, driven by supply, demand, geopolitical stability, and market speculation. Exxon Mobil Corporation (XOM), a major oil and gas company, has shown resilience despite market volatility due to its scale and diverse operations. The shift toward renewable energy and electric vehicles is expected to impact long-term oil demand.
## Executive Summary
The USF Quantitative Analysis Team developed a trading strategy for short selling XOM stock, using **ARIMA models (AutoRegressive Intergrated Moving Average)** to predict market volatility. The strategy was backtested on QuantConnect over a two-year period (2021–2023), and it focuses on trading decisions based on volatility metrics rather than real-time data.
## Insight Deep - Dive
- **Volatility threshold**: >20% (bearish, triggers short selling), <10% (bullish, cover shorts).
- **Shorting process**: Starts at 15% of the portfolio, increases in 5 phases.
- **Scheduled functions**: Monthly volatility updates and weekly trading decisions. The algorithm capitalizes on volatility to time short sales and mitigate risk through phased selling.
## Prediction chart
These are the 0utcomes of the ARIMA Model:
- **Consumer Price Index for All Urban Consumers, U.S**.: The model predicts a decline after 2020, deviating from historical growth. This suggests a potential deflationary trend or economic slowdown.
<br/> ![cpiii](https://github.com/user-attachments/assets/d6f59ea6-4448-4965-92c5-78051e47515b)
- **Consumer Price Index**: The forecast shows a steep upward trajectory, continuing the historical inflationary trend, indicating persistent price increases.
<br/> ![Image](https://github.com/user-attachments/assets/b7ee9872-76db-4748-94b1-c0e3de58c081)
- **Petroleum Consumption**: The model predicts a gradual decline, contrasting with historical stability and prior growth. This suggests potential structural shifts in energy consumption or policy changes
<br/> ![Petro](https://github.com/user-attachments/assets/d8585c3b-b88a-49e0-8344-58a66fbab468)





