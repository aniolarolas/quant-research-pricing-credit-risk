# J.P. Morgan Quantitative Research Job Simulation

This repository contains my work for the J.P. Morgan Quantitative Research job simulation.

The project is organized into four notebooks covering commodity pricing, storage valuation, credit risk modelling, and FICO score bucketing.

## Notebooks

### 01. Natural Gas Price Forecasting

Built a simple forecasting model for natural gas prices using a linear trend and annual seasonality.

### 02. Storage Contract Pricing

Developed a pricing function for a natural gas storage contract based on injection dates, withdrawal dates, storage costs, and operational constraints.

### 03. Credit Risk and Expected Loss

Estimated probability of default using borrower-level loan data and calculated expected loss using:

$$
Expected\ Loss = PD \times LGD \times EAD
$$

### 04. FICO Score Bucketing

Created a FICO score rating map using quantization and maximum likelihood bucketing to group borrowers by observed default behaviour.

## Main Skills

- Commodity price forecasting
- Storage contract valuation
- Credit risk modelling
- Expected loss estimation
- Probability of default modelling
- FICO score bucketing
- Maximum likelihood optimization
- Dynamic programming
- Model evaluation and interpretation

## Tools

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- Jupyter / Google Colab

## Repository Structure

```text
data/
notebooks/
README.md
