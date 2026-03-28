# Stochastic-Models-for-Asset-Returns
Comparing stochastic asset pricing models to real market data (NVDA): GBM vs Heston vs Merton:

Financial markets rarely behave the way classical models assume, returns are not perfectly normal, volatility is not constant, and extreme events occur more often than theory suggests.

This project investigates how well three foundational stochastic models Geometric Brownian Motion (GBM), Heston Stochastic Volatility, and Merton Jump Diffusion capture the behavior of real asset returns, we used 5(five) years of NVDA data, we moved from observed statistical properties to simulated price dynamics, and finally to a direct comparison between theory and reality.

Our goal was not just to simulate models, but to stress-test their assumptions against actual market data, revealing where they succeed, where they fail, and why calibration is essential in quantitative finance.

## Key Findings

- Real returns exhibit fat tails and volatility clustering, violating normality assumptions
- GBM fails structurally due to constant volatility and Gaussian returns
- Heston captures volatility clustering but requires calibration to avoid distortion
- Merton introduces jumps but is highly sensitive to jump intensity
- Model calibration is essential — structure alone is insufficient

This project is licensed under the MIT License.
