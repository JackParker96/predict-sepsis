# Early detection of sepsis in ICU patients

Sepsis leads to 6 million deaths globally every year, and sepsis treatments are the largest healthcare expenditure in the U.S. Every hour that detection of sepsis is delayed results in a 4-8% increase in the chance of death.

In this project, I worked on a team of three machine learning engineers to use the XGBoost and CatBoost algorithms to predict sepsis based on patient vital signs, lab test results, and demographics. We aimed to make accurate detections 6 hours earlier than sepsis was detected by hospital staff.

We dealt with a dataset that is very large (1.5 million rows), very imbalanced (under 2% of rows labeled as sepsis-positive), and very sparse (nearly 70% missing values). We compared various imputation and sampling techniques to uncover an effective machine learning pipeline for sepsis prediction.
