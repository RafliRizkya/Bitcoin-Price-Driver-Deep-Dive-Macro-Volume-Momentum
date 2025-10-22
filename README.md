# Bitcoin Price Driver Deep Dive Macro Volume Momentum

## Overview
This project presents a comprehensive, data-driven analysis of Bitcoin ($BTC) price action from 1 January 2020 to 17 October 2025. We move beyond daily headlines to identify the true, sustained drivers of market momentum. The analysis focuses on solving key market paradoxes related to External Forces (Macro/Politics) versus Internal Chaos (Volume/Industry failures).

## Data Source & Scope
- Source: Historical daily price and volume data obtained directly from the Binance API.
- Timeframe: 1 January 2020 – 17 October 2025 (5 years of data).
- Methodology: All analysis is internally consistent, derived from this single, high-volume dataset.

## Technical Analysis and Key Findings

### Momentum & External Drivers (The Core Truth)
![Average 14-Day Return by Event Category](Average%2014-Day%20Return%20by%20Event%20Category.png)
Our 14-day event analysis proves that Macroeconomic and Political forces are the highest drivers of sustained momentum, consistently outperforming other market catalysts. Conversely, major internal threats (Regulation, Industry structural failures) fail to create lasting negative trends, proving the market's high resilience.

### The Volume Paradox
![The Relationship Between Volume and Daily Return](The%20Relationship%20Between%20Volume%20and%20Daily%20Return.png)
Challenging conventional wisdom, our correlation test reveals a near-zero (0.00) linear relationship between daily volume and daily returns. Volume only signals the conviction or panic behind a move, not its direction.

### Technical Confirmation (MA Crossovers)
![BTC Price Movement](BTC%20Price%20Movement.png)
The analysis validates traditional indicators by mapping market events onto trend signals:
    - Golden Cross (MA50 > MA200): Consistently signaled the start of every major bull run.
    - Death Cross (MA50 < MA200): Warned of impending market declines or consolidation periods.


## Tools & Technologies
- Programming: Python

- Libraries: pandas (Data Manipulation), matplotlib / seaborn (Visualization), ccxt (API Data Acquisition), numpy (Numerical Operations).