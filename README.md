# Public Economic Data Analysis

This repository contains Python/Jupyter notebooks for processing public economic datasets and producing reproducible charts for policy-oriented analysis.

The focus is on Italy and international comparisons, covering productivity, firm structure, employment, tourism and energy prices.

## Repository content

| Notebook | Topic |
|---|---|
| `firm_size_value_added_eurostat.ipynb` | Firm size, number of enterprises and value added using Eurostat Structural Business Statistics |
| `tfp_oecd_italy_us.ipynb` | Total factor productivity comparison between Italy and the United States using OECD data |
| `female_employment_rate_europe_map.ipynb` | Female employment rate, age 20–64, mapped across European countries using Eurostat and GISCO data |
| `business_energy_prices_europe.ipynb` | Gas and electricity prices for the business sector in Italy, France, Germany and Spain |
| `value_added_by_macro_sector_italy_eurostat.ipynb` | Value added per person employed across Italian macro-sectors using Eurostat Structural Business Statistics |

## Data sources

The notebooks use public data mainly from:

- Eurostat, through direct downloads or APIs;
- OECD, through OECD Data Explorer or SDMX APIs;
- European Commission, Energy Prices and Costs Europe dashboard;
- GISCO, for geographical boundaries used in the employment map.

Useful links:

```text
Eurostat API:
https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-getting-started

OECD API:
https://www.oecd.org/en/data/insights/data-explainers/2024/09/api.html

European Commission – Energy Prices and Costs Europe:
https://energy.ec.europa.eu/data-and-analysis/energy-prices-and-costs-europe/dashboard-energy-prices-eu-and-main-trading-partners-2024_en

GISCO geographical data:
https://ec.europa.eu/eurostat/web/gisco/geodata