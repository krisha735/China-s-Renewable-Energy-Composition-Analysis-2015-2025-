# China's Renewable Energy Composition Analysis (2015–2025)

## Project Overview
This project is an interactive Tableau data visualization dashboard analyzing the evolution of renewable energy generation in China from 2015 to 2025. It tracks generation growth across four primary clean energy sources—**Bioenergy, Hydro, Solar, and Wind**—highlighting the structural shift and scaling of clean energy over a decade.

## Dashboard & Worksheets
* **Sheet 1: Overview of China's Energy Composition Generation (2015–2025)**
  * *Description:* A time-series visualization tracking the absolute generation growth (in TWh) of individual renewable sources over a 10-year span.
* **Sheet 2: Comparison of Compositions (2016 vs. 2025)**
  * *Description:* A comparative analysis highlighting the structural changes in energy generation volume between the baseline year (2016) and the final target year (2025).

## Dataset
* **Source File:** `china_renewables_release_long.csv` from Ember (global energy tank)
* **Key Fields:** `Date`, `Year`, `Month_Name`, `Quarter`, `Energy_Source`, `Generation (TWh)`, `Share of generation (%)`

## Tools & Technologies Used
* **Tableau Desktop:** Data modeling, calculated fields, filtering, and dashboard layout design.
* **CSV / Flat File Management:** Data structuring for time-series analytics.

## How to View
1. Download the repository.
2. Open `china_renewables_analysis.twb` using **Tableau Desktop** (or Tableau Reader).
3. Ensure the local path points correctly to the `china_renewables_release_long.csv` data source if prompted.
