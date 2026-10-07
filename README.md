# Motor Vehicle Insurance Portfolio Analysis By Power BI
## 1. Project Overview

This project uses Microsoft Power BI to analyzes data of a motor vehicle insurance portfolio, with the objective of understanding portfolio's performance, claims experience and differences across major risk segments.

Dataset in the project is from an open source - Motor vehicle insurance data, published by Jorge Segura-Gisbert, Josep Lledó and Jose M. Pavía in European Actuarial Journal: 
  Segura-Gisbert, J., Lledó, J. & Pavía, J.M. Dataset of an actual motor vehicle insurance portfolio. Eur. Actuar. J. 15, 241–253 (2025). https://doi.org/10.1007/s13385-024-00398-0

The dataset contains 105,555 rows and 30 variables, from a Spanish non-life motor insurance company. It includes following key features,
    * Date related information: Date_start_contract, Date_last_renewal, Date_next_renewal for policy management and risk assessment
    * Economic variables: Premiums, Cost_claims_year for assessing product's profitability
    * Risk related variables: Value_vehicle, Power, Length, Weight, etc.

## 2. Project Objective

The objective of this project is to analyze policy and claims data and to transform summary into an interactive analytical dashboard in terms of,
  * Portfolio performance monitoring
  * Claims analysis
  * Insurance metrics for management team

## 3. Dataset

Variables|	Description
---------|---------------
ID| Internal identification number assigned to each annual contract formalized by an insured. Each policyholder can have multiple rows in the dataset, representing different annuities of the product.
Date_start _contract|Start date of the policyholder's contract (DD/MM/YYYY).
Date_last_renewal|	Date of last contract renewal (DD/MM/YYYY).
Date_next_renewal|	Date of the next contract renewal (DD/MM/YYYY).
Distribution_channel |	Classifies the channel through which the policy was contracted. 0 for Agent and 1 for Insurance brokers.
Seniority |	Total number of years that the insured has been associated with the insurance entity, indicating their level of seniority.
Premium|	Net premium amount associated with the policy during the current year.
Cost_claims_year|	Total cost of claims for the insurance policy during the current year.
N_claims_year|	Total number of claims incurred for the insurance policy during the current year.
Type_risk|	Type of risk associated with the policy. Each value corresponds to a specific risk type: 1 for motorbikes, 2 for vans, 3 for passenger cars and 4 for agricultural vehicles
Area|	Dichotomous variable indicates the area. 0 for rural and 1 for urban (more than 30,000 inhabitants) in terms of traffic conditions.
Second_driver|	1 if there are multiple regular drivers declared, or 0 if only one driver is declared.
Year_matriculation|	Year of registration of the vehicle (YYYY).
Power|	Vehicle power measured in horsepower.
Cylinder|_capacity	Cylinder capacity of the vehicle.
Value_vehicle|	Market value of the vehicle on 31/12/2019.
Type_fuel|	Specific kind of energy source used to power a vehicle. Petrol (P) or Diesel (D).
Length|	Length, in meters, of the vehicle.
Weight|	Weight, in kilograms, of the vehicle.
