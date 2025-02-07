# Prioritizing Test Gaps by Risk in Industrial Practice: An Automated Approach and Multi-Method Study
_Supplemental web site for a software engineering research paper_

This supplementary web site enriches the paper "Prioritizing Test Gaps by Risk in Industrial Practice: An Automated Approach and Multi-Method Study". We list [research](#research-questions) and [interview questions](#interview-questions) of our semi-structured interviews that we conducted to answer RQ<sub>4</sub> (Expert Assessment) and provide access to the [plotting and sensitivity analysis scripts](#plotting-and-sensitivity-analysis-scripts) used for the paper charts, for reproducibility.

# RQ<sub>4</sub>: Semi-Structured Interviews with Quality Engineers

## Research Questions

1. How do Quality Engineers justify a higher risk of test gaps?
2. Do Quality Engineers consider our metrics used for the prioritization to be meaningful and representative with regard to the risk of test gaps?
3. Under which circumstances deviate Quality Engineers from their own ranking and follow the suggestions of our tool?
4. What reasons mention Quality Engineers that speak against the decisive criteria in the automated prioritization?
5. Do Quality Engineers consider test gaps risky which were automatically highly ranked but were not labeled as risky before?
6. What suggestions for changes to the automated ranking do Quality Engineers make for a more accurate risk assessment?
7. To what extent do subjective assumptions and experience of Quality Engineers play a role in the manual risk assessment of test gaps?
8. Do Quality Engineers believe that the test gap prioritization process can support them in their day-to-day work and if so, how?

## Interview Questions

 * Please weigh up the test gaps in pairs with regard to their risk.
 * Do you consider the metrics on which the risk score is based to be meaningful and representative of the actual risk?
 * Are there any deviations from the sorting just identified?
 * Can you explain whether subjective assumptions or empirical values play a role in your risk assessment?
 * Do you agree with the reasoning behind the automated ranking? Why?
 * Would you make changes to the metrics to align the automated ranking more closely with your risk assessment?
 * Do you think the tool would help you in your daily work as a technical quality engineer?

# Plotting and Sensitivity Analysis Scripts

Due to confidentiality agreements, we cannot provide access to the raw data obtained during our study.
For reproducibility reasons we publish scripts that generate the plots of our paper, which also contain the presented data in an aggregated manner, and the script which was used to conduct the sensitivity analysis and scenario analysis:

* [Statistics-TestGapRadar-public.ipynb](https://github.com/cqse/test-gap-risk-study/blob/main/Statistics-TestGapRadar-public.ipynb): Kernel density plot of scaled rankings for test gaps labeled as risky (RQ<sub>1</sub>)
* [Prioritization-Analysis-public.ipynb](https://github.com/cqse/test-gap-risk-study/blob/main/Prioritization-Analysis-public.ipynb): Correlation analysis and ANOVA (RQ<sub>2</sub>)
* [Sensitivity-Analysis-public.ipynb](https://github.com/cqse/test-gap-risk-study/blob/main/Sensitivity-Analysis-public.ipynb): Sensitvity Analysis and Scenario Analysis (RQ<sub>2</sub>)