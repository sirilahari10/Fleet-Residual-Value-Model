# Fleet Residual Value Forecasting

*Applying predictive modeling to optimize commercial vehicle lifecycle planning.*

## The Business Problem
In commercial fleet leasing, estimating the residual (resale) value of a vehicle is critical for pricing leases and determining the optimal replacement cycle. Relying solely on static depreciation tables leaves money on the table.

## The Solution
This repository demonstrates a machine learning approach to fleet valuation. 
* **Model:** A Random Forest Regressor trained on vehicle age, mileage, and preventative maintenance history.
* **Results:** The model successfully isolates how rigorous preventative maintenance schedules buffer against mileage-based depreciation.
* **Impact:** By integrating this logic into a Power BI dashboard via Python/SQL, fleet managers can dynamically identify the exact month a vehicle crosses its optimal resale threshold.
