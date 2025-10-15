---
output:
  pdf_document: default
  html_document: default
---

# R Projects Portfolio

## About this Repository

This repository showcases my R-based analytical workflows from past projects, including data cleaning, exploratory analysis with descriptive statistics and visualizations, statistical modeling, and predictive simulations.  
It also contains a **toolkit of reusable functions** designed to streamline these analyses.  

I am continuously adding more projects and expanding the toolkit.

## Projects

### Predicting Customer Detractors (Part 1): Analyzing Contextual Factors via Logistic Regression
* **Objective:** Identify contextual factors in customer service that are associated with lower customers’ likelihood to recommend the company.  
* **Methodology:** The project analyzes Net Promoter Scores (NPS) across contact channels, reasons for contact, and countries. The analytical steps include:  
  * **Data Simulation & Preparation:** Creating survey data and preparing datasets for analysis.  
  * **Exploratory Data Analysis:** Using data visualization (e.g., heatmaps) and descriptive statistics to uncover factor interactions.  
  * **Statistical Modeling:** Comparing regression models (linear, ordinal, binomial) to predict NPS scores across contextual factors.  
  * **Impact Evaluation:** Benchmarking potential improvements in customer service by factor.  
* **Tools & Libraries:** R with `car`, `VGAM`, `ordinal`, `psych`, `vcd`, `coefplot`, `ggplot2`, `tidyr`, `dplyr`, `openxlsx`, and `readxl`.  
* [View Project Notebook on RPubs](https://rpubs.com/galdovaldonavas/1335090)

---

### Predicting Customer Detractors (Part 2): Opportunity Analysis from Open Feedback
* **Objective:** Identify and quantify high-impact opportunities to increase customers’ likelihood of recommending the company.
* **Methodology:** Building on Part 1, this project investigates root causes of dissatisfaction through thematic analysis and simulates the potential business impact of addressing them. The analytical steps include:  
  * **Data Simulation & Preparation:** Generating datasets, subsamples, and preparing them for analysis.  
  * **Exploratory Data Analysis:** Descriptive statistics with 95% CI, displayed through bar plots, line graphs, and dot-and-whisker plots.  
  * **Statistical Modeling:** Binomial regression models predicting detractors, complaints, and specific issues.  
  * **Bootstrapping:** Estimating the reduction in detractors after correcting problems using bootstrap resampling.  
  * **Impact Evaluation:** Predictive analyses on the effect of addressing specific issues.  
  * **Prediction Validation:** Comparing predicted impact against observed KPI trends over time.  
* **Tools & Libraries:** R with `dplyr`, `openxlsx`, `ggplot2`, `vcd`, `psych`, `glmnet`, `boot`, and `MASS`.  
* [View Project Notebook on RPubs](https://rpubs.com/galdovaldonavas/1345416)

---

### Corporate responsibility Versus Easiness of E-Commerce Payments Methods: An Experimental Study
* **Objective:** Evaluate the business impact of introducing a controversial payment method on customer perceptions and behaviors, balancing ethical concerns against convenience benefits.  
* **Methodology:** Experimental analysis comparing customer responses between control (standard payment options) and experimental (including ControvPay) groups. Key analytical approaches: 
  * **Data Simulation & Preparation:** Simulated experimental assignment and questionnaire responses.   
  * **Exploratory Data Analysis:** Correlation matrices, group comparisons with 95% CIs, and diagnostic visualizations.  
  * **Hypothesis Testing:** Factorial ANOVA testing main and interaction effects.
  * **Bayesian Sensitivity Analyses:** Robustness checks with multiple prior specifications. 
  * **Causal Mechanisms:** Path analysis examining mediation through social responsibility perceptions. 
  * **Impact Evaluation:** Logistic models quantifying potential customer loss. 
* **Tools & Libraries:** R with `ggplot2`, `kableExtra`, `DiagrammeR`, `psych`, `MASS`, `car`, `corrplot`, `effectsize`, `BayesFactor`, and `PROCESS`.
* [View Project Notebook on RPubs](https://rpubs.com/galdovaldonavas/1355540)

---

📂 The R Markdown sources for all projects are available in the [Projects folder](https://github.com/galdovaldonavas/R_Research_Portfolio_and_Toolkit-/tree/main/Projects).

---

## Toolkit

The [Toolkit](https://github.com/galdovaldonavas/R_Research_Portfolio_and_Toolkit-/tree/main/Toolkit) contains reusable functions and procedures for:  
* Descriptive statistics with 95% confidence intervals  
* Data visualizations  
* Basic statistical tests (e.g, Chi-square, ANOVA...) 
* Multiple regression modeling  
* Predictive simulations

The toolkit is regularly updated with new functions and methods. Stay tuned for future additions.  

---

## Contact

Feel free to reach out if you have any questions or are interested in collaboration:  

* **GitHub:** [galdovaldonavas](https://github.com/galdovaldonavas)  
* **LinkedIn:** [Eduardo González Cabañes](https://www.linkedin.com/in/eduardo-gonzalez-caba%C3%B1es-79bb87a5/)  

