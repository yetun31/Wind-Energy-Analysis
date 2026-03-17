# Wind Speed Analysis and Wind Energy Potential Assessment

## Overview
This project performs a comprehensive wind resource assessment using approximately 10 years of hourly meteorological data. The objective is to evaluate wind characteristics at 50 m height and estimate the potential for wind energy generation.

The analysis combines statistical methods, wind energy principles, and time-series techniques to assess both wind behavior and energy production potential.

---

## Dataset
The dataset consists of hourly observations over ~10 years, including:

- Wind Speed at 50 m (WS50M)
- Wind Direction at 50 m (WD50M)
- Temperature at 2 m (T2M)
- Surface Pressure (PS)
- Relative Humidity at 2 m (RH2M)

---

## Methodology

The analysis follows a structured wind resource assessment workflow:

### 1. Exploratory Data Analysis (EDA)
- Wind speed distribution analysis
- Identification of central tendency and variability

### 2. Weibull Distribution
- Fitting Weibull distribution to wind speed data
- Understanding wind speed probability behavior

### 3. Wind Resource Assessment
- Mean wind speed estimation
- Wind power density calculation

### 4. Wind Direction Analysis
- Wind rose visualization
- Identification of dominant wind directions

### 5. Temporal Analysis
- Autocorrelation Function (ACF)
- Partial Autocorrelation Function (PACF)
- Evaluation of temporal dependence

### 6. Wind Speed Duration Curve (WSDC)
- Analysis of wind speed occurrence over time
- Assessment of turbine operating conditions

### 7. Annual Energy Production (AEP)
- Application of a simplified 2 MW turbine power curve
- Estimation of average annual energy generation

---

## Key Results

- **Mean Wind Speed:** 7.19 m/s  
- **Wind Power Density:** 388 W/m² (Class 3 – Moderate resource)  
- **Dominant Wind Direction:** West to South-West  
- **Wind Distribution:** Well represented by Weibull model  
- **Temporal Behavior:** Strong autocorrelation observed  

These results indicate that the site has **moderate-to-good potential for wind energy development**.

---

## Tools and Libraries

- Python
- pandas
- numpy
- matplotlib
- scipy
- statsmodels
- windrose

---
