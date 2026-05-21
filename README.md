# Retail Fixture Optimization Case Study

Award-winning senior practicum project focused on improving retail fixture space allocation across stores, product subcategories, and planning periods.

This project was completed as part of a University of Arkansas Data Science practicum. Our team won **Best Overall Project** for developing a business-facing optimization approach that balanced fixture capacity, stable vs. flexible space, and demand-based prioritization.

> Note: The original source code and raw datasets are not included due to project data restrictions and team/code access limitations. This repository serves as a public-facing case study summarizing the problem, methodology, optimization formulation, results, and recommendations.

## Business Problem

Retail stores must allocate limited fixture space across year-round, seasonal, and changing product categories. The challenge is to determine how much space should remain stable versus flexible while still responding to demand, store-level differences, and operational constraints.

The project focused on using historical fixture behavior and demand signals to support better space allocation recommendations.

## My Contribution

- Developed the optimization model used to generate fixture allocation recommendations.
- Integrated stable and flexible fixture estimates into allocation constraints.
- Used demand scores to prioritize allocation decisions by store, week, and subcategory.
- Produced optimization result summaries and business-facing insights.
- Helped translate technical model outputs into recommendations for professors, judges, and industry stakeholders.

## Methods

- Estimated stable vs. flexible fixture capacity using historical fixture allocation behavior.
- Combined fixture capacity estimates with demand signals.
- Formulated allocation decisions as a constrained optimization problem.
- Generated recommendations that balanced demand prioritization with operational feasibility.
- Summarized results through presentation visuals, report sections, and stakeholder-facing insights.

## Optimization Framing

**Decision Variable:**  
Recommended fixture allocation by store, product subcategory, and planning period.

**Objective:**  
Prioritize fixture space toward higher-demand categories while respecting available capacity.

**Core Constraints:**

- Store-level fixture capacity
- Stable fixture allocation requirements
- Flexible fixture availability
- Product subcategory feasibility
- Demand-based prioritization logic

## Tools

R · data.table · lpSolve · Excel · PowerPoint · Business Reporting · Data Visualization

## Results

- Produced fixture allocation recommendations across store and product subcategory combinations.
- Identified opportunities to better balance stable year-round space with flexible seasonal/clearance space.
- Translated optimization outputs into executive-facing recommendations.
- Helped deliver an award-winning final practicum presentation and report.
- Awarded **Best Overall Project** in the senior practicum.

## Repository Contents

```text
retail-fixture-optimization-case-study/
├── README.md
├── report/
│   └── retail-fixture-optimization-report.pdf
├── presentation/
│   └── retail-fixture-optimization-presentation.pdf
├── visuals/
│   └── selected-project-figures
└── methodology/
    └── optimization-model-summary.md
