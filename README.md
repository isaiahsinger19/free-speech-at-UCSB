# Free Speech at UCSB 🗣️  
**PSTAT 122 Final Project — University of California, Santa Barbara**  
**Author:** Isaiah Singer  
**Date:** June 2025  

## Overview  
This project explores how UCSB students perceive the state of free speech on campus and whether the **framing of a statement** changes their opinions.  
By conducting an experiment using a **Generalized Randomized Block Design**, I analyzed how tone and emphasis affected responses while controlling for class standing (Freshman, Sophomore, Junior, Senior).  

The primary goal was to determine if different framings of free speech — respectful exchange, perceived threat, or scholarly growth — influenced how strongly students agreed with each perspective.

## Objectives  
- Measure UCSB students’ agreement with various framings of free speech.  
- Evaluate whether **statement tone** affects perceived restrictiveness.  
- Test statistical significance across groups using **ANOVA** and **permutation methods**.  
- Assess model assumptions and conduct **post-hoc power analysis** for insight into sample adequacy.  

## Tools & Techniques  
- **R packages:** readxl, ggplot2, dplyr, broom, pwr, knitr  
- **Design:** Generalized Randomized Block Design  
- **Statistical Tests:** Two-way ANOVA, Tukey pairwise comparisons, permutation test  
- **Validation:** Normality checks (QQ-plot, Shapiro-Wilk), variance testing, post-hoc power analysis  

## Data Summary  
- **Sample size (n):** 21 UCSB students  
- **Treatment groups:**  
  1. Respectful exchange of ideas  
  2. Threat to free speech framing  
  3. Scholarly/critical thinking framing  
- **Block factor:** Student class standing (Freshman–Senior)  
- **Response variable:** Rating of agreement (1–10 scale)  

## Key Findings  
- Neither **treatment** nor **block factor** showed statistically significant effects (ANOVA p ≈ .99).  
- **Permutation test** confirmed the ANOVA result (p ≈ .992).  
- **Pairwise comparisons** indicated no significant differences between treatments.  
- **Post-hoc power analysis** showed that ~300 participants would be needed to detect a small effect (f ≈ .10, 80% power).  
- **Normality and variance checks** revealed mild skewness and nonlinearity but not enough evidence to reject normality.  

## Visualization Examples  
- **Boxplot:** Rating distribution across treatments  
- **Scatterplot:** Rating distribution by treatment and class standing  
- **Histogram & QQ-Plot:** ANOVA residual normality check  
- **Power Curve:** Sample size vs. effect size (for 80% power)

## Conclusions  
- Differences in statement framing **did not significantly alter** students’ views on free speech.  
- The experiment suggests that **students at UCSB hold consistent attitudes** toward speech restrictiveness, regardless of presentation.  
- Small sample size likely limited the study’s power, but findings align with prior research suggesting broad support for free expression.  

## Reflection  
This project demonstrated applied statistical design — from **experimental setup** to **model validation and interpretation** — while addressing a **socially relevant topic**.  
It highlights the importance of sample size and assumption testing in real-world research, as well as the complexity of quantifying human attitudes.  

## Project Files  
- [`scripts/PSTAT122FinalProject.Rmd`](scripts/PSTAT122FinalProject.Rmd) — Main R Markdown file  
- [`outputs/PSTAT122FinalProject.pdf`](outputs/PSTAT122Final) 

---

*Created by Isaiah Singer — Data Analyst/Scientist | R, Python, SQL | UCSB Statistics & Data Science*
