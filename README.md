# Maternal Education and the Demand for Maternal & Child Health Services in Bangladesh

This repository contains the Python analysis for examining the impact of maternal education and household wealth on the utilization of maternal and child health services in Bangladesh. The analysis is based on data from the **Bangladesh Demographic and Health Survey (BDHS) 2022**.

The main analysis is contained within the Jupyter Notebook: `main.ipynb`.

## Overview
This project applies economic frameworks (such as the Grossman model of health demand) to understand health-seeking behaviors. It estimates the average marginal effects of education and wealth on five key maternal health service outcomes using Probit regression models.

### Key Outcomes Analyzed:
1. **ANC 4+ Visits**: Mother attended 4 or more antenatal care visits.
2. **Facility Delivery**: Delivery took place in a health facility.
3. **Doctor-Attended ANC**: Antenatal care was provided by a qualified doctor.
4. **Iron Supplementation**: Mother took iron supplements during pregnancy.
5. **1st ANC in 1st Trimester**: First antenatal care visit occurred within the first 3 months of pregnancy.

## Requirements
The project uses standard data science and econometrics libraries in Python. You will need Python 3 installed along with the following packages:

```bash
pip install pandas numpy scipy matplotlib seaborn statsmodels openpyxl
