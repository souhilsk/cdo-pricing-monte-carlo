# CDO Pricing with Monte Carlo Simulation

NYU Financial Engineering project to price a $100MM CDO using a Monte Carlo simulation.

The model generates 10,000+ paths for a 10-bond collateral pool and distributes cash flows through a multi-tranche waterfall to value the CDO.


### Key Quantitative Concepts Implemented

* Monte Carlo Simulation (10,000+ paths)
* Correlated Default Modeling (Gaussian Copula & Hazard Rates)
* Cash-Flow Waterfall Algorithm
* Tranche Sizing (Binary Search for 'Aa' Target EL)
* Risk Metric Calculation (PD, LGD, Expected Loss)
* Market-Consistent Valuation (Covariance-based Risk-Charge 'k')

### Dependencies

* `numpy`
* `pandas`
* `scipy`
* `matplotlib`
