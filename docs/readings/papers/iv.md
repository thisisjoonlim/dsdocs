---
layout: default
title: IV
parent: Papers
grand_parent: Readings
---

# Applications of IV 
{: .no_toc .d-inline .print-title-size }

---

#### Summary 
{: .no_toc }

1. TOC
{:toc}

---

## Estimating the Return to Education

How would you measure how much an additional schooling would impact one's income? 
{: .pb-3 }

This is a difficult question to answer as there exists an "ability bias" in estimates of the economic return to education that more able idividuals in the labor market get more schooling, perhaps because of better access to captical markets. Angrist et al. addressed the potential bias in "years of schooling" using "quarter of birth" as an intrumental variable for education and claimed that an additional year of schooling would bring around 8-9% increase in weekly earnings in their publication [1][2]. Individuals' season of birth is related to their educational attainment because of the combined effects of school start age policy and compulsory school attendance laws. In most school districts, individuals born in the beginning of the year start school at a slightly older age, and therefore are eligible to drop out of school after completing fewer years of schooling than individuals born near the end of the year.
{: .pb-3 }

### Framework
{: .no_toc }

$$ \\Y = \gamma_{0} + \gamma_{1} X_{1} + \rho S + \epsilon \tag $$
{ .text-center }

$$ \\S = \delta_{0} + \delta_{1} X_{1} + \delta_{2} X_{2} + \eta \tag $$
{ .text-center }

- $$ Y $$ : ln(Weekly Wage)
- $$ S $$ : Years of Schooling
- $$ X1 $$ : Years of Birth Dummies
- $$ X2 $$ : Quarter of Birth IV (with Compulsory School Attendance)
- $$ \gamma, \delta, \rho $$ : vectors of coefficients
{: .pb-3 }

### Conclusion
{: .no_toc }

<div class="reading_img_container">
    <img src = "/assets/images/iv_table_1.png">
</div>

- an additional year of schooling would bring around 8-9% increase in weekly earnings.
- 25 percent of potential dropouts remain in school because of compulsory schooling laws.
- a valid identification strategy because date of birth is unlikely to be correlated with omitted earnings determinants.
- return to education is close to the OLS estimate, suggesting that there is little ability bias in conventional estimates.
{: .pb-3 }

### Note
{: .no_toc }

Angrist et al. introduced the concept of *Local Average Treatment Effect (LATE)* for Instrumental Variables (IV) [2], where the treatment effect for the subset of the sample that takes the treatment if and only if they were assigned to the treatment. In an ideal experiment, all subjects assigned to treatment are treated, while those that are assigned to control will remain untreated. In reality, however, the compliance rate is often imperfect, which prevents researchers from identifying the ATE. In such cases, estimating the LATE becomes the more feasible option.

*[1] Angrist, J. D., & Keueger, A. B. (1991). [Does compulsory school attendance affect schooling and earnings?](https://www.nber.org/papers/w3572.pdf). The Quarterly Journal of Economics, 106(4), 979-1014.*
{: .fs-2 }

*[2] Angrist, J. D., & Imbens, G. W. (1995). [Two-stage least squares estimation of average causal effects in models with variable treatment intensity](https://scholar.harvard.edu/imbens/files/wo-stage_least_squares_estimation_of_average_causal_effects_in_models_with_variable_treatment_intensity.pdf). Journal of the American statistical Association, 90(430), 431-442.*
{: .fs-2 }

---

## Treat vs. Intent-to-Treat in Online Experiments


Estimating Network Effects Using Naturally Occurring Peer Notification Queue Counterfactuals
Two-Stage Least Squares For A/B Tests From Twitch

