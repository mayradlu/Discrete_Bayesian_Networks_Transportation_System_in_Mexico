# Discrete Bayesian Networks Transportation System in Mexico
## General Information
This project aims to analyze the transportation system in Mexico using Bayesian networks to identify the means of transportation most used by the population and evaluate their level of satisfaction in terms of safety and efficiency. Using the database provided by the [National Mobility and Transportation Survey of the Institute of Legal Research of UNAM](http://www.losmexicanos.unam.mx/movilidadytransporte/encuesta_nacional.html), various stages of preprocessing, modeling and analysis were carried out to obtain significant insights.

## Project Structure
**Data Preprocessing**
Python was used to clean and prepare the database, ensuring that the data was in a suitable format for subsequent analysis with Bayesian networks.

**Modeling with Bayesian Networks**
R was used to create 3 Directed Acyclic Graphs (DAGs) and evaluate their performance using BIC and AIC criteria. The model that best fit the data was selected to infer probabilities and analyze dependencies between key variables.
<p align="center">
  <img src="https://github.com/user-attachments/assets/db992e37-08e6-4028-9d21-daa2997cc3e0" alt="imagen">
</p>

## Results
This is an example of the queries made to the DAGs in order to respond to probabilities for certain events.
![imagen](https://github.com/user-attachments/assets/7170c809-fa76-4472-9652-8000a391cabf)


