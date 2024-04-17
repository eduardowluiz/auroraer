# auroraer
# Technical exercise for Energy Modeller at Aurora Energy Research

## Summary of the Technical Exercise

**Applicant:** Eduardo Weide Luiz

**Date:** 17/04/2024

**Position:** Energy Modeller

**Company:** Aurora Energy Research


For the technical exercise, I crafted a solution tailored to conditions resembling the Brazilian energy market, where only prices for the following day are available. I used the half-hourly price data for the next 24 hours across Markets 1 and 2, and a single total price value for Market 3. Using a linear optimization approach, I aimed to maximize profit using only Markets 1 and 2 and compared the estimated profit to the fixed price of Market 3, while taking into account the available battery storage. The method involved comparing the profit potential from the optimization model against the option of purchasing energy directly from Market 3 and utilizing the stored energy for the next 24-hour period. If the optimization model indicated higher profit, I adopted that strategy; otherwise, I procured energy from Market 3. The charging and discharging loss of 0.05 were included in the profit calculations. Different configurations could be used, for example a minimum battery storage at the end of the optimization day.


The model was developed using Python and the libraries: 

-	GEKKO
-	Numpy
-	Pandas


