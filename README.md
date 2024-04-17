# auroraer
Technical exercise for Energy Modeller at Aurora Energy Research

Summary of Technical Exercise

Applicant: Eduardo Weide Luiz

Date: 17/04/2024

Position: Energy Modeller

Company: Aurora Energy Research

For the technical exercise, I crafted a solution tailored to conditions resembling the Brazilian energy market, where hourly prices for the following day are available. I generated simulated half-hourly price data for the next 24 hours across Markets 1 and 2, and a single total price value for Market 3. Using a linear optimization approach, I aimed to maximize profit by exploiting price differences between Markets 1 and 2 compared to the fixed price of Market 3, while taking into account available battery storage. The method involved comparing the profit potential from the optimization model against the option of purchasing energy directly from Market 3 and utilizing stored energy for the next 24-hour period. If the optimization model indicated higher profit, I adopted that strategy; otherwise, I procured energy from Market 3 and managed stored energy accordingly. 

This optimization model was developed using the python libraries: 
GEKKO
Numpy
Pandas

