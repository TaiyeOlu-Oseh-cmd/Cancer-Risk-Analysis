# Cancer Risk Factors Analysis (Excel & Power BI)

![Image](https://github.com/user-attachments/assets/07432885-5f9b-4230-be9a-ce95dc4c5f51)

## Project Summary
This project analyzes cancer risk across five cancer types—Breast, Lung, Colon, Prostate, and Skin—using simulated patient-level data. The analysis applies descriptive statistics and correlation analysis to explore how demographic, lifestyle, dietary, and environmental factors relate to overall cancer risk.

---

## Analysis Questions and Results

### Question 1: What is the distribution of patients across cancer types?

| Cancer Type | Number of Patients |
|------------|-------------------|
| Breast     | 460 |
| Colon      | 418 |
| Lung       | 527 |
| Prostate  | 305 |
| Skin      | 290 |
| **Total**  | **2000** |

**Insight:** Lung cancer has the highest number of patients, while skin cancer has the lowest representation.

---

### Question 2: How does the average age vary by cancer type?

| Cancer Type | Average Age |
|------------|------------|
| Breast     | 62 |
| Colon      | 61 |
| Lung       | 61 |
| Prostate  | 72 |
| Skin      | 62 |
| **Overall Average** | **63** |

**Insight:** Prostate cancer patients have the highest average age.

---

### Question 3: How do lifestyle risk factors differ across cancer types?

| Cancer Type | Avg Smoking | Avg Alcohol Use | Avg Obesity |
|------------|-------------|-----------------|-------------|
| Breast     | 3.76 | 5.13 | 8.27 |
| Colon      | 3.97 | 4.82 | 5.16 |
| Lung       | 8.85 | 5.17 | 5.30 |
| Prostate  | 3.85 | 5.04 | 5.38 |
| Skin      | 3.76 | 4.93 | 5.31 |
| **Overall Avg** | **5.16** | **5.04** | **5.97** |

**Insight:** Lung cancer patients record significantly higher smoking levels than other cancer types.

---

### Question 4a: What is the average overall cancer risk score by cancer type?

| Cancer Type | Avg Risk Score |
|------------|---------------|
| Breast     | 0.43 |
| Colon      | 0.47 |
| Lung       | 0.50 |
| Prostate  | 0.39 |
| Skin      | 0.46 |
| **Overall Avg** | **0.45** |

**Insight:** Lung cancer has the highest average risk score, while prostate cancer has the lowest.

---

### Question 4b: How are patients distributed across risk levels?

| Cancer Type | High | Low | Medium | Total |
|------------|------|-----|--------|-------|
| Breast     | 13 | 89 | 358 | 460 |
| Colon      | 29 | 59 | 330 | 418 |
| Lung       | 47 | 34 | 446 | 527 |
| Prostate  | 3 | 93 | 209 | 305 |
| Skin      | 10 | 49 | 231 | 290 |
| **Total**  | **102** | **324** | **1574** | **2000** |

**Insight:** The majority of patients fall within the medium-risk category across all cancer types.

---

### Question 5: What is the relationship between protective lifestyle factors and cancer risk?

**Correlation Matrix**

|                     | Fruit & Veg Intake | Physical Activity | Risk Level |
|---------------------|-------------------|------------------|------------|
| Fruit & Veg Intake  | 1.000 | — | — |
| Physical Activity   | 0.013 | 1.000 | — |
| Risk Level          | -0.126 | 0.077 | 1.000 |

**Insight:**  
- Fruit and vegetable intake shows a very weak negative correlation with risk level  
- Physical activity shows a very weak positive correlation with risk level  
- There is no meaningful linear relationship between diet and physical activity  

**Conclusion:** Cancer risk in this dataset is influenced by multiple interacting factors rather than any single protective lifestyle behavior.

---

## Tools Used
- Microsoft Excel: Pivot tables, descriptive analysis, correlation analysis
- Power BI: Interactive dashboards and data visualization

---

## Use Case
This project is intended for educational and portfolio purposes, demonstrating applied data analytics and visualization skills within a public health context.
