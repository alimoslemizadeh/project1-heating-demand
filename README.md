# Residential Building Heating Demand Analysis (Germany)

## Project Overview
This project presents a data-driven, preliminary heating demand analysis for a multi-family residential building located in Germany.  
The goal is to demonstrate a transparent and explainable energy assessment workflow using Python.

## Problem Statement
In early design or retrofit stages, architects and energy consultants need a fast and reliable method to estimate heating demand and understand the contribution of building envelope and ventilation losses.

## Methodology
- Simplified steady-state heat loss model
- Transmission losses calculated from U-values and surface areas
- Ventilation losses calculated using air change rate (ACH)
- Annual heating demand estimated using Heating Degree Days (HDD)

## Key Assumptions
- Single-zone building
- Constant indoor temperature
- HDD-based climate approach
- No internal or solar gains considered

## Results
- Total heat loss coefficient: ~1345 W/K
- Annual heating demand: ~96,800 kWh/year
- Specific heating demand: ~80.7 kWh/m²·year

## Visual Outputs
- Heat loss breakdown (transmission vs ventilation)
- Annual heating demand bar chart

## Tools & Skills
- Python
- Pandas
- Data analysis
- Building energy fundamentals
- Data visualization

## Limitations
This simplified model is intended for early-stage analysis and comparison purposes. Detailed dynamic simulations would be required for final design decisions.

