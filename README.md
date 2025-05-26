# The Financing Cost for Renewables Estimator (FinCoRE)

The Wacc Estimator is a Python project to estimate and model the cost of capital for energy transition technologies at a national scale and with temporal granularity. Input data is taken from [Damodaran](https://pages.stern.nyu.edu/~adamodar/) and [Ember Climate](https://ember-energy.org/data/yearly-electricity-data/), with the approach extending on the one developed by [IRENA](https://www.irena.org/-/media/Files/IRENA/Agency/Publication/2023/May/IRENA_The_cost_of_financing_renewable_power_2023.pdf) 


## Requirements

[Python](https://www.python.org/) version 3+


Required libraries:
 * streamlit
 * xarray
 * pandas
 * numpy
 * folium
 * streamlit_folium
 * branca
 * altair
 * plotly
 * kaleido
 * openpyxl
 * matplotlib
 * seaborn
 
## SETUP

### Download the data in the repository and update, if required
The data saved under the DATA folder was downloaded in early 2025, so may need updating. Download the relevant Country Risk Premium and Electricity Generation data from Damodaran and Ember, if an update is required.

### Set up the WACC model
With the required libraries installed, the model should just require creation of a main script to run the wacc_calculator_v1.py code. Specifically, it should call the calculate_yearly_waccs method or calculate_future_waccs, with specification of the desired year, technology, country, and assumptions for projections forward (to include interest rate changes, GDP per capita improvements and/or 2030 technology targets)


## LICENSE
BSD 3-Clause License
Copyright (C) 2023-2025  Luke Hatton
All rights reserved.

See `LICENSE` for more detail

## Citation

The LCOH code was developed by Luke Hatton, who can be contacted at l.hatton23@imperial.ac.uk

L Hatton, 2025.  Historical and Future Projected Costs of Capital for 10 energy technologies across 176 countries (LCOH) model. Currently under review.

