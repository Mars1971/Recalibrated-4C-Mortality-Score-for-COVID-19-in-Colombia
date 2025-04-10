# Recalibrated 4C Mortality Score for COVID-19 in Colombia
</br>
</br>

### Introduction and Recommendation for the 4C Mortality Score Calculator in Predicting COVID-19 Mortality
</br>
</br>

Accurate risk stratification is vital for making hospitalization decisions in COVID-19 patients. This study assessed the 4C Mortality Score's ability to predict 30-day mortality in COVID-19 patients presenting to emergency departments (EDs). We conducted an external validation using a cohort of patients from seven high-complexity hospitals in Colombia, who presented between March 2020 and September 2021.

</br>

The 4C model showed the best discrimination (AUC 0.72, 95% CI 0.71–0.74) and clinical utility, though its calibration was suboptimal. Thus, we conducted a logistic recalibration in which both the model's intercept and slope were adjusted to better fit our data.  After recalibration, the 4C model achieved an observed/expected ratio of 1 while preserving its predictive accuracy. 

</br>

The new formula for the recalibrated model is:

</br>

### New model = intercept_new (-1.049) + overall slope (0.781) * original 4C model logit

adjusting all logistic model coefficients. An online calculator based on this recalibrated model is presented below.

</br>

The 4C Mortality Score outperformed other models in predicting mortality. Decision curve analysis indicated its value in guiding hospitalization decisions at a ≥4% mortality risk threshold. When used alongside clinical judgment, it can improve risk assessment, guide hospitalization decisions, and help optimize resource allocation. Recalibration and decision curve analysis enhance its practical application.

</br>
</br>

### Access to calculator at the following link:

</br>

https://martinrondon.shinyapps.io/Recalibrated_4C_Mortality_Score_for_COVID_19_in_Colombia/



