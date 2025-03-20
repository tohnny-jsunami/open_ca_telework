# The Open CA Telework Dashboard Project
In Spring 2024, the State of California Telework Dashboard was abruptly taken down. The Dashboard contained information that makes a strong case for telework.

This is an open source project intended to recover, revive, renew the initial dashboard or create an equivilent alternative. All interested parties are encouraged to contribute to this effort.

## Resources
- https://www.telework-dashboard.com/
- [DGS telework github repo](https://github.com/cadgs/telework)
- [initial telework dashboard URL](https://telework.govops.ca.gov/tracking-telework/)
- [PDF of Statewide Telework Dashboard from DGS](https://www.documents.dgs.ca.gov/Telework/PDF%20Output/Statewide%20Telework%20Dashboard%20-%20DTSC.pdf)

## Soure Data
- [Statewide Hybrid Workforce]("https://catalog.data.gov/dataset/statewide-hybrid-workforce")
- [DGS Telework Data](https://data.ca.gov/dataset/dgs-telework-data)

## Requirements
Please see the `requirements.txt` file to install the dependencies for this repo. This repo was intended to be developed with the [jupyter/datascience-notebook docker image](https://hub.docker.com/r/jupyter/datascience-notebook)

## Recovered About Sections
Users have provided the original "About" section text.

>#### Description: 
This dashboard is for CA departments’ telework data submitted.
>
>#### Audience: 
This dashboard and its data are intended to be available to the public.
>
>#### Data sources: 
>
>Each department provides their own data, based on their individual internal telework tracking systems.  Guidance on how to collect this data is available on the Reporting Requirements page.  Cumulative savings estimates are based on the submitted data since October 2021. 
>
>Over time, the number of total departments may fluctuate due to reorganization and departments coming online or shutting down operations. 
>
>Expected staff count is derived primarily from the enacted Governor's Budget and direct department input where staff count is not available. Prior to July 1, 2023 the total expected staff count was sourced from State Controller's Office actuals for each department. 
>
>#### Assumptions:
>
>This dashboard represents a generalized estimation using available data with the following assumptions.  
>
>**Commute calculation:** All employees are assumed to commute to work daily in a vehicle with no other passengers. Commute savings are figured only on miles from the alternate work location to the office site and does not account for driving to errands, daycare, schools, or other facilities route or during the workday.  No precise data is available for employee’s use of public transportation or carpools, so these commute methods are not currently factored in. We consider it reasonable to assume that actual savings (in both dollars and CO2) are probably less than shown, due to this uncertainty. Holidays and vacation days are excluded from calculations. Actual telework days may differ from the reported counts due to various individual circumstances. In limited cases where the commute distance could not be calculated, the average commute distance of all other employees is used. Data for employees with PO Box (0 miles) or commuting over 100 miles one-way were excluded in the average calculation. 
>
>**Energy Savings Calculation:** Historic average gas prices in California come from the U.S. Energy Information Administration’s Weekly Retail Gasoline and Diesel Prices report. Mid-grade gasoline prices are used for calculations. The average fuel economy for gasoline passenger vehicles is 24.4 mpg, per the California Energy Commission’s analysis of the Department of Motor Vehicles’ registration data for personal gasoline vehicles, as of the end of 2019.  IRS mileage rate is taken from the IRS standard mileage reimbursement.
>
>[**CO2 Avoided Calculation:**](https://www.epa.gov/energy/greenhouse-gas-equivalencies-calculator-calculations-and-references) The common conversion factor of 8,887 grams of CO2 emissions per gallon of gasoline was used. Conversion factor for carbon sequestered is 0.77 metric ton CO2/acre/year sequestered annually by one acre of average U.S. forest (from the Environmental Protection Agency’s Greenhouse Gases Equivalencies Calculator References). 