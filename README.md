# Audit_risk_classfication
The goal of the usecase is to help the auditors by building a classification model that can predict the fraudulent firm on the basis the present and historical risk factors.

Data description:-
Sector_score-Historical risk score value of the target-unit using analytical procedure
LOCATION_ID-Unique ID of the city/province.
PARA_A-Discrepancy found in the planned expenditure of inspection and summary report A in Rs (in crore).
Score_A
Risk_A
PARA_B-Discrepancy found in the unplanned expenditure of inspection and summary report B in Rs (in crore).
Score_B
Risk_B
TOTAL-Total amount of discrepancy found in other reports Rs (in crore).
numbers-Historical discrepancy score
Score_B.1
Risk_C
Money_Value-Amount of money involved in misstatements in the past audits.
Score_MV
Risk_D
District_Loss
PROB
RiSk_E
History
Prob
Risk_F
Score
Inherent_Risk
CONTROL_RISK
Detection_Risk
Audit_Risk-Total risk score using analytical procedure
Risk-Risk Class assigned to an audit-case. (Target Feature)

Many risk factors are examined from various areas like past records of audit office, audit-paras, environmental conditions reports, firm reputation summary, on-going issues report, profit-value records, loss-value records, follow-up reports etc. After in-depth interview with the auditors, important risk factors are evaluated and their probability of existence is calculated from the present and past records.

Process performed :-
The goal of the usecase is to help the auditors by building a classification model that can predict the fraudulent firm on the basis the present and historical risk factors. I have started with understanding the bussiness case, and started performing eda on the dataset
come across with various insight in the data set which will help the auditer, Built a classfication model based on the dataset and checked with the accuracy of the model
