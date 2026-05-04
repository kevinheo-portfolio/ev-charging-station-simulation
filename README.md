**Overview**

The United States must triple its public EV charging infrastructure by 2030. This project provides a data-driven capacity planning model for a 20-port public EV charging hub. By building a discrete event simulation (DES) in Python, we analyzed over 450,000 real-world charging sessions to identify system bottlenecks and evaluate capital expansion strategies against non-linear demand growth.

**Tech Stack & Methodologies**

- Languages & Libraries: Python, SimPy, Pandas, NumPy, Matplotlib, SciPy
- Analytical Methods: Discrete Event Simulation (DES), M/M/c Queuing Theory, Little's Law Validation, Statistical Distribution Fitting (Lognormal, Exponential, Mixture Models)
- Domain: Operations Management, Capacity Planning, Scenario Analysis

**Key Findings & Business Impact**

- Identified the True Bottleneck: Proved via simulation that Level 2 (L2) chargers were the binding constraint (72% utilization, 32-minute wait), while expensive DC Fast Chargers (DCFC) were vastly over-provisioned.
- Prevented Wasted CapEx: Demonstrated that adding more DCFCs at urban locations yielded zero system improvement, saving hypothetical capital expenditure.
- Optimized Capacity & OpEx: Modeled a combined intervention of adding 6 L2 ports alongside dynamic peak pricing and overstay fees, which dropped customer abandonment (balk rate) from 20.2% to 3.1% and reduced wait times by 80%.
- Forecasted 2030 Demand: Stress-tested the network against NREL 2030 projections, proving that deferred expansion would lead to a 52.6% customer loss rate.
