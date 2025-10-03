# Creative Gaming: Uplift Modeling for "Space Pirates" Campaign
# Overview

This project focuses on optimizing targeting strategies for the Zalon campaign in Space Pirates, a game by Creative Gaming. Traditional propensity-to-buy models were inefficient, often wasting ads on customers who would have purchased anyway or discouraging customers with overexposure. By applying Uplift Modeling, we identified the customers most likely to be influenced by ads, leading to more efficient marketing spend and improved campaign adoption.

# Objective

Analyze 60,000 customers split into control (no ads) and treatment (ads shown) groups.

Identify the persuadable segment—customers who are most responsive to ads.

Compare Uplift vs. Propensity-to-Buy Models to determine the superior targeting approach.

Maximize incremental profit and minimize wasted ad spend.

# Approach

Segmented customer base into control and treatment groups (30K each).

Applied Uplift Modeling across multiple algorithms:

Logistic Regression

Neural Networks

Random Forest

XGBoost

Evaluated performance using Uplift Plots, Incremental Uplift Plots, and Profit Analysis.

Determined optimal targeting thresholds to avoid “Do-Not-Disturb” customers and maximize ROI.

# Results

Uplift models consistently outperformed propensity models by focusing only on persuadable customers.

Achieved significant incremental profit gains (e.g., $55K+ improvements across Neural Network, Random Forest, and XGBoost).

Reduced targeting pool (25–40% of customers vs. 50%) while maximizing efficiency and ROI.

Prevented over-targeting, ensuring smarter ad spend and improved customer experience.

📊 Repository Contents

cg-uplift.ipynb — Jupyter notebook with full uplift modeling pipeline.

data/ — Datasets used for analysis (control & treatment groups).

creative-gaming.pdf — Case study with methodology and findings.

# Tools & Technologies

Python (Pandas, NumPy) for data manipulation

Neural Netowrk, Random Forest and XGBoost for machine learning models

Matplotlib for data visualization
