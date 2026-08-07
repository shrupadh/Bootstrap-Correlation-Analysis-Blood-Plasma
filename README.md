# Bootstrap-Correlation-Analysis-Blood-Plasma
Learn nonparametric bootstrap resampling to estimate the sampling distribution, bias, standard error, and confidence interval of Pearson's correlation coefficient using Python.

## Project Overview

This project demonstrates the use of **bootstrap resampling** to estimate the sampling distribution of the Pearson correlation coefficient between plasma volume measurements obtained using the **Hurley** and **Nadler** methods.

The analysis includes exploratory data analysis (EDA), data preparation, Pearson correlation analysis, and bootstrap estimation of the correlation coefficient, bias, standard error, and 95% confidence interval using Python.

---

## Dataset

The dataset contains plasma volume measurements for **99 subjects** using two different measurement methods:

- Hurley Method
- Nadler Method

---

## Project Workflow

- Load and explore the dataset
- Perform exploratory data analysis (EDA)
- Reshape the data from long to wide format
- Compute the Pearson correlation coefficient
- Generate bootstrap samples
- Estimate the bootstrap sampling distribution
- Calculate:
  - Bootstrap Mean
  - Bootstrap Bias
  - Bootstrap Standard Error
  - 95% Bootstrap Confidence Interval

---

## Results

- Pearson Correlation (r): **0.9902**
- Bootstrap Mean: **0.9903**
- Bootstrap Bias: **0.000063**
- Bootstrap Standard Error: **0.00174**
- 95% Confidence Interval: **(0.9866, 0.9934)**

The results indicate a **very strong positive linear relationship** between the Hurley and Nadler plasma volume measurements. Bootstrap resampling confirmed that the estimated correlation coefficient is stable and highly precise.

---

## Figures

### Distribution of Plasma Volume Measurements

![Distribution](figures/plasma_distribution.png)

### Plasma Volume Measurements by Method

![Boxplot](figures/plasma_boxplot.png)

### Hurley vs. Nadler Measurements

![Scatter Plot](figures/hurley_vs_nadler_scatter.png)

### Bootstrap Distribution of the Pearson Correlation Coefficient

![Bootstrap Distribution](figures/bootstrap_distribution.png)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Repository Structure

```text
├── data/
├── figures/
├── Bootstrap_Correlation_Analysis.ipynb
├── Bootstrap_Correlation_Analysis.pdf
├── README.md
└── requirements.txt
```
