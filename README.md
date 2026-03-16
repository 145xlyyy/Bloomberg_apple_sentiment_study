# Apple Sentiment vs Market

A data analysis project exploring the relationship between social-media sentiment and stock market performance using Apple Inc. (AAPL) as a case study.

This project investigates whether public discussion on social media reflects or predicts financial market movements, particularly around major product launch events.

---

## Project Overview

This study analyzes the dynamic relationship between **Twitter sentiment and Apple stock performance** from **2016 to 2025**.  

Using event-based analysis around Apple iPhone launch periods, the project examines whether social-media sentiment can serve as an indicator of market behavior.

Key questions include:

- Do abnormal returns appear around major Apple launch events?
- Is there a statistical relationship between social-media sentiment and stock price changes?
- Can sentiment data predict future stock returns?

---

## Dataset

The analysis combines multiple data sources:

**Financial Market Data**

- Apple (AAPL) weekly price data  
- S&P 500 weekly market returns  
- Event windows around Apple launch announcements  

Sources:
- Bloomberg Terminal  
- Yahoo Finance  

**Social Media Data**

- Twitter positive sentiment count  
- Twitter negative sentiment count  
- Twitter publication volume  

Source:
- Bloomberg social sentiment dataset

---

## Methodology

The study applies several statistical techniques to examine relationships between sentiment and market performance.

### Pearson Correlation
Measures the strength of the linear relationship between social-media sentiment and stock returns.

### 2×2 Contingency Analysis
Examines whether positive sentiment weeks tend to coincide with positive abnormal returns.

### Chi-Square Test
Tests whether sentiment direction and market return direction are statistically independent.

### Lag-1 Regression
Evaluates whether sentiment from the previous week can predict next-week stock returns.

---

## Key Findings

The analysis suggests that:

- Social-media sentiment often reflects **current market mood**.
- However, sentiment does **not provide strong predictive power** for future stock returns.
- Abnormal returns around Apple launch events appear but are not consistently driven by sentiment changes.

Overall, social sentiment acts more like a **mirror of investor mood** rather than a reliable forecasting signal.

---

## Project Structure
