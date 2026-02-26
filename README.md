# SaaS Churn Crisis Diagnosis (80/20 Framework)

## Executive Summary

In Q3, BizGrow’s churn increased from 4% to 12%.

Using 80/20 concentration analysis and hypothesis-driven testing, we identified the primary structural driver of churn.

- 84% of churn originates from the lowest 20% engagement segment
- Customers who never activate churn at ~100%
- Activated customers churn at only ~6–7%
- Product performance and regional effects are not primary drivers
- The structural issue is low-quality acquisition combined with activation failure
- A 30% improvement in early activation reduces churn from 12.1% to 10.6% (~13% relative reduction)

Activation is the highest-leverage operational control point.

---

# Business Problem

Leadership observed a sudden spike in churn and proposed four possible causes:

1. Dashboard performance issues  
2. Market/region saturation  
3. Support overload  
4. Declining customer quality  

The objective was to determine the single largest structural driver of churn and deliver one measurable intervention.

---

# Analytical Framework

The project follows a structured 80/20 diagnostic methodology:

1. Data cleaning and validation  
2. Master dataset construction  
3. 80/20 churn concentration analysis  
4. Hypothesis testing (H1–H4)  
5. Business impact modeling  

---

# Key Findings

## 1. Churn Concentration

- 84% of churn is concentrated within the lowest 20% engagement segment.
- Non-activated users account for nearly all churn within that segment.

## 2. Hypothesis Testing Results

| Hypothesis | Result |
|------------|--------|
| H1: Product performance | Not supported |
| H2: Market/region saturation | Not supported |
| H3: Support overload | Weakly supported |
| H4: Low-quality acquisition | Strongly supported |

Churn is structurally driven by customers who:
- Never activate
- Belong to small (1–10 employee) accounts
- Have weaker onboarding quality

---

# Quantified Impact Simulation

Current churn: 12.13%  
Simulated churn after 30% activation lift: 10.55%  
Relative reduction: ~13%

Because non-activated customers churn at ~100%, even partial improvements in activation generate outsized retention gains.

---

# Final Recommendation

1. Implement 48-hour activation milestone tracking  
2. Trigger automated onboarding intervention if no login is detected  
3. Prioritize small (1–10 employee) accounts with guided onboarding  
4. Introduce acquisition quality scoring to reduce low-fit pipeline inflow  

Expected Outcome:  
Reducing non-activation by 30% reduces overall churn by ~13%, with disproportionate impact among small accounts.

---

# Tech Stack

- Python
- pandas
- numpy
- matplotlib
- seaborn

---

# Skills Demonstrated

- Hypothesis-driven analysis  
- 80/20 concentration modeling  
- Customer segmentation  
- Feature engineering  
- Business impact simulation  
- Executive communication of analytical results  

---

# Why This Project Matters

This case demonstrates structured problem-solving in a real-world churn crisis scenario.

Rather than building a predictive model, the focus was identifying the highest-leverage operational control point — resulting in a clear, quantifiable business recommendation.