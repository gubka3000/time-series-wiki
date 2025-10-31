# Time Series Analysis: Wiki Page Views for "Eyes Wide Shut"

## Overview
Analysis of monthly Wikipedia page views for *"Eyes Wide Shut"* (English) from **July 2015 to September 2025** (123 points). The goal is to explore trends, seasonality, cyclicality, and volatility using Python.

## Key Findings
- **Trend:** Steady upward trend, more pronounced in the second half.  
- **Seasonality:** Peaks in **summer (Jul–Aug)** and **pre-New Year (Dec)**; sharp drops in February.  
- **Volatility:** Deviations are denser in early years; larger spreads after 2022.  
- **Stationarity:** Log-transformed and differenced series are approximately stationary.  
- **Cycles:** Repeating seasonal patterns (~6 months and ~12–15 months) detected via ACF, PACF, Welch method, and STFT.  
- **Smoothing:** Triple exponential smoothing and polynomial detrending capture trend and seasonality effectively.  
- **Peaks:** Most peaks occur pre-New Year; summer peaks also visible but less consistent.  