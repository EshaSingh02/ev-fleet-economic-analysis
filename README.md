# EV Fleet Economic Analysis

## Techno-Economic Evaluation of EV, CNG and Diesel Commercial Vehicles

This project presents a scenario-based techno-economic analysis of electric, CNG and diesel commercial vehicles using a Total Cost of Ownership (TCO) framework.

The objective is to evaluate the economic attractiveness of electric vehicle adoption under different operating and cost conditions, with particular emphasis on annual vehicle utilization, vehicle purchase price, energy prices and charging infrastructure costs.

---

## Project Overview

Fleet electrification decisions cannot be based only on the upfront purchase price of a vehicle.

A vehicle with a higher initial purchase cost may become economically attractive over its operating lifetime because of lower energy and operating costs.

This project therefore evaluates the economics of EV adoption using:

- Five-year Total Cost of Ownership (TCO)
- Annual vehicle utilization
- Energy/fuel operating costs
- EV purchase-price sensitivity
- Energy-price sensitivity
- Charging infrastructure cost
- Break-even analysis
- Payback analysis
- Fleet-scale economics
- Scenario-based comparison

The analysis compares three vehicle technologies:

| Technology | Vehicle |
|---|---|
| Electric | Tata Ace Pro EV |
| CNG | Tata Ace Pro Bi-Fuel |
| Diesel | Tata Ace Pro Diesel |

---

## Key Questions

The analysis investigates the following questions:

1. Which vehicle technology has the lowest five-year TCO?
2. How does annual vehicle utilization affect EV economics?
3. How sensitive is EV TCO to the initial purchase price?
4. How do changes in electricity, CNG and diesel prices affect the comparison?
5. How much additional charging infrastructure cost can an EV economically absorb?
6. At what operating conditions does EV adoption become economically favorable?
7. How do the economics change when the analysis is extended from one vehicle to a fleet?

---

## Methodology

The analysis uses a Total Cost of Ownership framework.

### Five-Year TCO

The basic formulation is:

$$
TCO_{5yr} =
Purchase\ Cost +
5\text{-}Year\ Energy\ Cost
$$

Annual energy cost is estimated using:

$$
Annual\ Energy\ Cost =
Annual\ Utilization
\times
Energy\ Consumption\ per\ km
\times
Energy/Fuel\ Price
$$

The resulting costs are projected over the five-year analysis period.

---

## Baseline Scenario

The baseline analysis uses an annual utilization of:

**25,000 km/year**

The baseline vehicle purchase prices are:

| Vehicle | Purchase Price (₹ lakh) |
|---|---:|
| EV | 6.50 |
| CNG | 4.99 |
| Diesel | 5.99 |

Under the baseline assumptions, the model estimates:

| Vehicle | 5-Year TCO (₹ lakh) |
|---|---:|
| EV | ~8.18 |
| CNG | ~11.59 |
| Diesel | ~13.15 |

The EV therefore has the lowest estimated five-year TCO under the baseline scenario.

---

## Baseline Economic Advantage

At 25,000 km/year, the estimated EV savings are approximately:

- **₹3.41 lakh vs CNG**
- **₹4.98 lakh vs Diesel**

These savings are calculated relative to the corresponding five-year TCO of the conventional vehicle alternatives.

---

## Sensitivity Analysis

### 1. Annual Utilization

Annual utilization is varied across:

- 5,000 km
- 10,000 km
- 15,000 km
- 20,000 km
- 30,000 km
- 40,000 km
- 50,000 km
- 60,000 km

The analysis shows that EV economic advantage increases with higher annual utilization because the lower operating cost is realized over a larger number of kilometres.

### 2. EV Purchase Price

EV purchase price is varied by:

- −20%
- −10%
- 0%
- +10%
- +20%

The results show that increasing EV purchase price increases its five-year TCO and reduces its savings relative to CNG and diesel.

### 3. Energy Price

Electricity, CNG and diesel prices are varied to evaluate the sensitivity of the economic comparison to energy-price assumptions.

### 4. Charging Infrastructure

Additional EV charging infrastructure cost is varied to determine how much infrastructure expenditure can be absorbed before the EV loses its TCO advantage relative to CNG.

---

## Results

### Baseline TCO

![Baseline TCO](outputs/figures/baseline_tco_comparison.png)

### EV Economic Advantage vs Annual Utilization

![Utilization Sensitivity](outputs/figures/utilization_sensitivity.png)

### EV TCO Sensitivity to Purchase Price

![Purchase Price Sensitivity](outputs/figures/purchase_price_sensitivity.png)

### EV Savings Sensitivity to Purchase Price

![Purchase Price Savings](outputs/figures/purchase_price_savings_sensitivity.png)

### Energy Price Sensitivity

![Energy Price Sensitivity](outputs/figures/energy_price_sensitivity.png)

### Charging Infrastructure Sensitivity

![Infrastructure Sensitivity](outputs/figures/infrastructure_sensitivity.png)

---

## Key Findings

1. The EV has the lowest estimated five-year TCO under the baseline assumptions.

2. EV economic advantage increases with annual vehicle utilization.

3. Higher EV purchase prices reduce the economic advantage of electrification.

4. Energy-price assumptions materially affect the relative economics of EV, CNG and diesel vehicles.

5. Additional charging infrastructure expenditure reduces EV savings, but the baseline model indicates that a significant infrastructure cost can be accommodated while maintaining an economic advantage over CNG.

6. Fleet-scale deployment increases the absolute monetary savings as the number of vehicles increases.

---

## Limitations

This analysis is a scenario-based techno-economic assessment and should not be interpreted as a guaranteed prediction of future costs.

The current model does not fully capture all possible real-world factors, including:

- Vehicle financing costs
- Insurance
- Taxes
- Residual/resale value
- Battery degradation
- Battery replacement
- Detailed maintenance costs
- Charging downtime
- Real-world driving variability
- Time-varying electricity and fuel prices

The results are therefore dependent on the assumptions and parameters defined in the model.

---

## Future Improvements

Potential extensions include:

- Battery degradation modelling
- Battery replacement economics
- Discounted cash-flow analysis
- Net Present Value (NPV)
- Internal Rate of Return (IRR)
- Residual-value modelling
- Maintenance-cost modelling
- Real-world charging losses
- Charging downtime
- Payload-dependent energy consumption
- Monte Carlo uncertainty analysis
- Emission reduction analysis
- Optimization of fleet replacement strategy

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Repository Structure

```text
ev-fleet-economic-analysis/
│
├── README.md
├── notebooks/
│   └── EV_Fleet_Economic_Analysis.ipynb
│
├── data/
│   └── README.md
│
├── outputs/
│   ├── figures/
│   └── tables/
│
├── src/
│   └── README.md
│
├── requirements.txt
└── .gitignore
```
How to Run

-Clone the repository:git clone https://github.com/<your-username>/ev-fleet-economic-analysis.git
-Install the required packages: pip install -r requirements.txt
-Open the notebook: jupyter notebook
-Run

Author

Esha Singh

M.Tech — Sustainable Energy Engineering
Indian Institute of Technology Kanpur

##Disclaimer

This project is intended for academic and analytical purposes. 
The results are based on the assumptions and input parameters defined in the model,and should not be treated as a commercial procurement recommendation without further validation using real-world operational and financial data.

