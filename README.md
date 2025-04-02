# 📘 Depression and Social Indicators in UK Older Adults  
**INF6029 Data Analysis Final Report**

This project investigates the relationship between depression and various demographic, health, and behavioural indicators among older adults in the UK, using data from Wave 7 of the English Longitudinal Study of Ageing (ELSA).

📄 Report Title: *Exploring the Relationship Between Depression and Demographic, Health, and Behavioural Factors*  
📅 Submission Date: January 13, 2025  
📊 Tool: SPSS (Statistical Package for the Social Sciences)  
🧑‍💻 Author: Shixiong Xu  
📝 Word count: ~2730 words  
📁 Dataset: ELSA Wave 7 (n = 532 after filtering)

## 🧠 Research Objectives

1. **RQ1**: How are demographic, health, and behavioural factors individually associated with depression?
2. **RQ2**: When considered together, which factors remain significant predictors of depression in older adults?

## 🔍 Variables Used

| Category          | Variable               | Type     |
|-------------------|------------------------|----------|
| Demographic       | Gender                 | Binary   |
|                   | Marital Status         | Nominal  |
|                   | Ethnic Group           | Nominal  |
| Health Factor     | Long-standing Illness  | Binary   |
| Behavioural       | Smoking Behaviour      | Binary   |
|                   | Drinking Frequency     | Ordinal  |

## 🧪 Methodology

- **Data Source**: English Longitudinal Study of Ageing (ELSA) Wave 7  
- **Software**: SPSS  
- **Analysis Workflow**:
  - Descriptive statistics
  - Chi-square tests of independence for bivariate associations
  - Binary logistic regression to identify significant predictors

## 📈 Key Findings
- **Significantly Associated with Depression**:
  - **Long-standing illness** (OR = 1.595, p = 0.033)
  - **Smoking** (OR = 1.763, p = 0.021)
- **No Significant Association Found**:
  - Gender, marital status, ethnicity, drinking frequency

## 🔬 Interpretation
The findings align with previous literature suggesting that chronic illness and smoking are strong predictors of depression among elderly populations. However, demographic variables (gender, ethnicity, marital status) showed **no significant predictive value**, contrary to prior studies, potentially due to:
- Small sample sizes in subgroups
- Regional/cultural differences
- Self-reported data limitations

## ⚠️ Limitations
- Reliance on **self-reported data** (susceptible to social desirability bias)
- **Uneven sample distribution** across ethnic groups
- Cross-sectional design limits causal inference

## 🧭 Future Work
- Use **longitudinal data** to better explore causality
- Control for **socioeconomic status** and **mental health stigma**
- Extend to **interactive dashboards** or integrate into predictive models with Python or R

## 📚 References
Key studies cited in the report include:
- World Health Organization (2023, 2024)
- Copeland et al. (1999)
- An & Xiang (2015)
- Dibato et al. (2022)
- McCarter et al. (2018)
- Inaba et al. (2005)

For the full list, refer to the `report.pdf` or `report.docx` in this repository.

## 📂 Repository Structure
```plaintext
├── README.md
├── INF6029_Data_Analysis_Report_Shixiong_Xu.pdf
