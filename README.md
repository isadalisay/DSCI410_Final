# CAHOOTS and EPD Proportion and Diversion Analysis

This project analyzes 911 emergency call data from Eugene, Oregon, with a focus on **agency response patterns**, particularly between the **Eugene Police Department (EPD)** and **CAHOOTS** (Crisis Assistance Helping Out On The Streets). The goal is to explore **call distribution**, **diversion rates**, and how these patterns have changed over time—especially in light of **CAHOOTS’ recent service suspension in Eugene**.

---

## Language and Tools

- **Language**: R  
- **Libraries**:  
  - `ggplot2`  
  - `lubridate`  
  - `tidyverse`  
  - `nnet`

---

## Techniques

- Descriptive statistics and proportions  
- Grouped visualizations over time  
- Multinomial logistic regression  
- Heatmap of predicted agency response

---

## Caveats

- This is **observational data**, so patterns described are **not causal**.
- Trends may be influenced by **unmeasured factors** like policy changes, call coding, or dispatch protocol differences.
- For stronger causal insights, **additional modeling** (e.g., random forests, quasi-experimental designs) is recommended.

---
