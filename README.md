# EV Fleet Economic Analysis

## Techno-Economic Evaluation of EV, CNG and Diesel Commercial Vehicles

This project presents a scenario-based techno-economic analysis of electric, CNG and diesel commercial vehicles using a Total Cost of Ownership (TCO) framework.

The objective is to evaluate the economic attractiveness of electric vehicle adoption under different operating and cost conditions, with emphasis on annual vehicle utilization, vehicle purchase price, energy prices and charging infrastructure costs.

## Project Overview

Fleet electrification decisions cannot be based only on upfront purchase price. A vehicle with a higher initial purchase cost may become economically attractive over its operating lifetime because of lower energy and operating costs.

This project evaluates EV adoption using:

- Five-year Total Cost of Ownership (TCO)
- Annual vehicle utilization sensitivity
- Energy/fuel operating costs
- EV purchase-price sensitivity
- Energy-price sensitivity
- Charging infrastructure cost
- Break-even analysis
- Fleet-scale economics
- Scenario-based comparison

The analysis compares:

| Technology | Vehicle |
|---|---|
| Electric | Tata Ace Pro EV |
| CNG | Tata Ace Pro Bi-Fuel |
| Diesel | Tata Ace Pro Diesel |

## Key Questions

1. Which vehicle technology has the lowest five-year TCO?
2. How does annual vehicle utilization affect EV economics?
3. How sensitive is EV TCO to the initial purchase price?
4. How do changes in electricity, CNG and diesel prices affect the comparison?
5. How much additional charging infrastructure cost can an EV economically absorb?
6. At what operating conditions does EV adoption become economically favorable?
7. How do the economics change when the analysis is extended to a fleet?

## Methodology

The analysis uses a Total Cost of Ownership framework.

### Five-Year TCO

$$
TCO_{5yr} = Purchase\ Cost + 5\text{-}Year\ Energy\ Cost
$$

Annual energy cost is estimated using:

$$
Annual\ Energy\ Cost = Annual\ Utilization \times Energy\ Consumption\ per\ km \times Energy/Fuel\ Price
$$

The resulting operating costs are projected over the five-year analysis period.

## Baseline Scenario

The baseline analysis uses an annual utilization of **25,000 km/year**.

| Vehicle | Purchase Price (₹ lakh) | 5-Year TCO (₹ lakh) |
|---|---:|---:|
| EV | 6.50 | ~8.18 |
| CNG | 4.99 | ~11.59 |
| Diesel | 5.99 | ~13.15 |

Under the baseline assumptions, the EV has the lowest estimated five-year TCO.

## Baseline Economic Advantage

At 25,000 km/year, the estimated five-year EV savings are approximately:

- **₹3.41 lakh vs CNG**
- **₹4.98 lakh vs Diesel**

These values are calculated relative to the corresponding five-year TCO of the conventional alternatives.

## Sensitivity Analysis

### Annual Utilization

Annual utilization is varied across 5,000 to 60,000 km/year to evaluate how increasing vehicle usage affects the economics of electrification.

### EV Purchase Price

EV purchase price is varied by −20%, −10%, 0%, +10% and +20% to assess the effect of upfront vehicle cost on five-year TCO and savings.

### Energy Price

Electricity, CNG and diesel prices are varied to evaluate the sensitivity of the economic comparison to energy-price assumptions.

### Charging Infrastructure

Additional EV charging infrastructure cost is varied to determine how much infrastructure expenditure can be absorbed before the EV loses its TCO advantage relative to CNG.

## Key Findings

1. The EV has the lowest estimated five-year TCO under the baseline assumptions.
2. EV economic advantage increases with annual vehicle utilization.
3. Higher EV purchase prices reduce the economic advantage of electrification.
4. Energy-price assumptions materially affect the relative economics of EV, CNG and diesel vehicles.
5. Additional charging infrastructure expenditure reduces EV savings, while the baseline model indicates that an infrastructure cost can be accommodated while maintaining an economic advantage over CNG.
6. Fleet-scale deployment increases the absolute monetary savings as the number of vehicles increases.

## Limitations

This is a scenario-based techno-economic assessment and should not be interpreted as a guaranteed prediction of future costs.

The current model does not fully capture all possible real-world factors, including:

- Vehicle financing costs
- Insurance and taxes
- Residual/resale value
- Battery degradation and replacement
- Detailed maintenance costs
- Charging downtime
- Real-world driving variability
- Time-varying electricity and fuel prices

Results are therefore dependent on the assumptions and input parameters defined in the model.

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

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Repository Structure

```text
ev-fleet-economic-analysis/
├── README.md
├── EV_Fleet_Transition_Analysis.ipynb
├── requirements.txt
└── .gitignore
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/EshaSingh02/ev-fleet-economic-analysis.git
cd ev-fleet-economic-analysis
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook EV_Fleet_Transition_Analysis.ipynb
```

4. Run the notebook cells from top to bottom.

## Author

**Esha Singh**  
M.Tech — Sustainable Energy Engineering  
Indian Institute of Technology Kanpur

## Disclaimer

This project is intended for academic and analytical purposes. The results are based on the assumptions and input parameters defined in the model and should not be treated as a commercial procurement recommendation without further validation using real-world operational and financial data.
