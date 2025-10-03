# Creative Gaming: Uplift Modeling for "Space Pirates" Campaign
#### Overview:
Zalon’s gaming campaign needed an optimized customer targeting strategy. Traditional propensity-to-buy models were inefficient because they also targeted customers who would have purchased regardless of ads, or worse, discouraged others from buying. The challenge was to identify the persuadable customers most likely to be influenced by advertisements while avoiding wasted ad spend and customer irritation.

#### Action / Tasks:

Segmented customers into treatment (ads shown) and control (no ads) groups of 30,000 each.

Applied uplift modeling (vs. propensity-to-buy modeling) to measure the causal impact of ads.

Built and tested multiple machine learning models (Logistic Regression, Neural Networks, Random Forest, and XGBoost).

Conducted comparative analysis of uplift vs. propensity models using uplift plots, incremental uplift plots, and profit values.

Determined optimal targeting thresholds to maximize incremental profit and reduce negative impact.

#### Results:

Uplift models consistently outperformed propensity-to-buy models, identifying customers who truly needed ad persuasion.

Neural Network, Random Forest, and XGBoost uplift models showed significant incremental profit gains (e.g., $55K+ profit improvement compared to propensity models).

Optimal targeting reduced the customer pool (e.g., targeting 25–40% instead of 50%) while maximizing efficiency and ROI.

The uplift model avoided over-targeting and “Do-Not-Disturb” customers, ensuring higher profit, lower costs, and better customer experience.

#### Conclusion:
Uplift modeling is a superior strategy for ad targeting in gaming campaigns, yielding higher incremental revenue, reducing wasted ad spend, and focusing on the customers most likely to be influenced by marketing efforts.

#### Repository Contents

'cg-uplift.ipynb' — Jupyter notebook with full uplift modeling pipeline.

'data/' — Datasets used for analysis (control & treatment groups).

'creative-gaming.pdf' — Case study with methodology and findings.


## Tools & Technologies

Programming Language: Python

Libraries: scikit-learn, XGBoost, TensorFlow/Keras, pandas, numpy, matplotlib

Models: Logistic Regression, Neural Networks, Random Forest, XGBoost

Evaluation Metrics: Uplift plots, Incremental uplift plots, Profit analysis
