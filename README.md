Data Source: 
This project uses a publicly available dataset from the CDC Behavioral Risk Factor Surveillance System (BRFSS), accessed via Kaggle. 
The dataset is fully de-identified and contains no protected health information (PHI). It includes population-level indicators related to diabetes, health behaviors, and access to care. 
Privacy Statement: 
No PHI is included in this repository. All data are public, aggregated, and compliant with HIPAA safe harbor standards. 
The questions that I am asking and working to answer is: How can we reduce bias in the algorithm while also reducing burnout within the leadership team?
How can health system leaders use routinely collected risk-factor data (e.g., BMI, blood pressure, cholesterol, smoking, physical activity) to identify and address inequities in diabetes risk—while ensuring that predictive models do not systematically overlook or misclassify high‑risk patients?

Figures:
<img width="901" height="422" alt="image" src="https://github.com/user-attachments/assets/5411e1e3-8d3f-44fd-a9f7-c55321970819" />
<img width="420" height="193" alt="image" src="https://github.com/user-attachments/assets/842f7203-2d6e-49fb-bb5e-59893bae524e" />
<img width="344" height="180" alt="image" src="https://github.com/user-attachments/assets/45b71e0f-5ed4-4896-af95-55cd637c610d" />

ai_insights.md in /analysis/
Your pivot table shows:
No diabetes (0): Avg BMI ≈ 27.7
Prediabetes (1): Avg BMI ≈ 30.7
Diabetes (2): Avg BMI ≈ 31.9
This is a clean, interpretable pattern:
As BMI increases, diabetes severity increases.
Now let’s turn that into leadership‑level actions.
Leadership Actions to Improve Diabetes Prevention & Equity
1. Strengthen early‑risk identification workflows
Because BMI rises sharply between “no diabetes” and “prediabetes,” leaders can:
Implement automatic alerts in the EHR for patients with BMI ≥ 30
Create standardized referral pathways to nutrition, lifestyle coaching, or CHWs
Ensure prediabetes screening is not dependent on clinician memory or bias
This reduces missed opportunities for early intervention.
2. Build targeted, equity‑centered outreach programs
BMI alone doesn’t tell the whole story — but it can help leaders identify populations who may need more support.
Leadership actions:
Use BMI + other risk factors to identify high‑risk ZIP codes or clinics
Partner with community organizations to deliver culturally relevant prevention programs
Ensure outreach materials reflect local language, culture, and lived experience
This shifts prevention from clinic‑only to community‑embedded.
3. Address structural barriers that influence BMI and diabetes risk
Leaders can use this pattern to advocate for:
Access to affordable healthy foods
Safe spaces for physical activity
Transportation support for appointments
Insurance coverage for nutrition counseling and CHW services
This moves beyond individual behavior to structural determinants.
4. Improve data quality and equity monitoring
Your BMI pattern is useful — but incomplete without equity context.
Leadership actions:
Add fields like race, rurality, insurance status, and income to dashboards
Monitor whether certain groups are under‑screened or late‑diagnosed
Require equity stratification in all diabetes‑related reports
This prevents models from reinforcing disparities.
5. Build a prevention dashboard for managers
Using your pivot table as a starting point, leaders can create a dashboard showing:
Average BMI by clinic
Prediabetes rates
Screening completion
Risk‑factor combinations (e.g., BMI + high BP)
Managers can then:
Identify clinics needing more resources
Track improvement over time
Celebrate teams reducing risk factors
6. Train clinicians on bias‑aware risk assessment
Because BMI is not equally predictive across all populations, leaders should:
Provide training on culturally responsive care
Emphasize that BMI is one indicator, not a moral judgment
Encourage clinicians to consider social drivers alongside BMI
This reduces stigma and improves trust.
7. Integrate CHWs into diabetes prevention workflows
CHWs can:
Provide culturally grounded education
Help patients navigate food insecurity or transportation
Support lifestyle changes outside the clinic
Leadership can:
Fund CHW positions

Embed them in primary care teams

Track their impact on prediabetes progression
