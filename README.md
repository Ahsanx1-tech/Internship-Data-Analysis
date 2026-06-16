# Internship-Data-Analysis
This project investigates the factors influencing internship recruitment success in the technology sector. Using a dataset of 151 candidates, the study explores whether traditional academic metrics (CGPA, College Tier) and practical experience (Internships, Projects) are reliable predictors of technical proficiency and soft skills.
# Key Research Objectives
Selection Bias Analysis: Investigating the disparity in selection rates between Tier 1 and Tier 2 institutions.

Aptitude Testing: Determining if college prestige (Tier) correlates with higher aptitude scores.

Predictive Modeling: Using Multiple Linear Regression to see if CGPA and experience can predict coding test performance.

# Phase 1: Bivariate Analysis & Group Comparisons
Two-Sample Proportion Test: Found a significant selection rate gap (76% for Tier 1 vs. 18.75% for Tier 2).

One-Way ANOVA: Proved that College Tier has no significant impact on student aptitude scores (p=0.56).

Two-Sample T-Test: Analyzed the impact of extracurricular activities on soft skill scores.

# Phase 2: Predictive Modeling (OLS Regression)
Model: Coding_Test_Score=β0 + β1(CGPA) + β2(Projects)  +β3 (Internships)  +ϵ

Diagnostics: Conducted Multicollinearity checks (VIF), Normality analysis of residuals (Jarque-Bera) and Joint Significance tests (Wald Test).

Findings: The model revealed a low R^2(2.3%), indicating that traditional resume metrics are weak predictors of actual technical performance.

Actionable Insights for HR
Eliminate Tier-Filtering: Data suggests aptitude is independent of university prestige.

Skill-Based Hiring: Since resume metrics are weak predictors, mandatory hands-on coding assessments are essential to identify high-potential talent.

Diversity Audit: The significant gap in selection rates between tiers suggests a need to review the initial screening funnel for bias.
