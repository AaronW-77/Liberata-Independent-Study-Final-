# Liberata-Independent-Study-Final (Liberata Scenario-Based Financial Modeling Project)

## Author
[Aaron Wang]: Lead Developer, Financial Model Designer, and Report Author

---

## Disclaimer
This project was completed as part of an Independent Study under the supervision of Prof. Luyao Zhang at Duke Kunshan University.

---

## Acknowledgments
I would like to sincerely thank Prof. Luyao Zhang for her guidance and valuable feedback throughout this project.  
Special thanks to my product team leader, Anish Verma, and my teammates for their insightful discussions and support.  
I also acknowledge Han Zhang and Patrick Prochazka for leading the Liberata Project and providing the context for this study.  
Finally, I thank all members of the Liberata Project team for their collaboration and contributions.

---

## Project Overview

This project develops a **scenario-based financial modeling framework** to evaluate strategic decisions for early-stage growth of the Liberata platform.

Instead of treating financial projections as precise forecasts, this model reframes projections as **hypothesis-testing tools**, allowing us to systematically analyze how different strategic levers impact financial performance.

The model focuses on three key dimensions:

- Growth (user adoption dynamics)  
- Timing (revenue conversion)  
- Cost (operational scaling)  

---

## Research Objective

The primary objective of this project is:

- To evaluate how different strategic levers influence revenue, cost, and profitability  
- To identify which strategies accelerate breakeven  
- To provide a structured, reproducible framework for early-stage decision-making  

---

## Methodology

### Scenario-Based Financial Modeling

The model is designed as a **controlled experiment system**, where each scenario isolates a specific strategic lever:

- **Scenario 1 (Growth):** Accelerated early-stage adoption  
- **Scenario 2 (Timing):** Earlier revenue conversion  
- **Scenario 3 (Cost):** Lean operational scaling  

Each scenario modifies a subset of parameters while holding others constant, enabling direct comparison of impact.

---

### Model Structure

The financial model follows a modular structure:

- Revenue = Users × Price  
- Cost = Salary + Cloud + Marketing + SG&A + CapEx  
- EBIT = Revenue − Cost  

All calculations are implemented in Excel and structured for transparency and reproducibility.

---

## Key Assumptions

- Constant pricing growth over time  
- Stable conversion rates across cohorts  
- No market saturation constraints  
- Cost components follow predefined growth rates  

---

## Results Summary

Key findings from the model include:

- **Growth-driven strategies (Scenario 1)** generate the highest long-term revenue and EBIT  
- **Timing improvements (Scenario 2)** enhance early cash flow without changing long-term scale  
- **Cost discipline (Scenario 3)** improves profitability through reduced operational expenses  

Each strategy impacts a different dimension of performance:

- Growth → Scale  
- Timing → Cash flow  
- Cost → Efficiency  

---

## Model Limitations

- Deterministic model (no stochastic variation)  
- No competitive dynamics modeled  
- No market feedback or saturation effects  
- Early-stage assumptions lack full empirical validation  

Therefore, results should be interpreted as **directional insights rather than precise predictions**.

---

## Replicability

All model assumptions, parameter values, and calculations are explicitly documented in the Excel file.
This ensures that the results can be fully reproduced and verified by other researchers.

## Future Work

Potential extensions include:

- Incorporating stochastic simulation
- Modeling competitive dynamics
- Validating assumptions with real-world data
