# Hi-SECURE-POEM-2024
## Overview
This script is designed for generating the main figures of the POEM project article. It includes Jupyter notebooks for plotting figures using Python and RMD files for plotting figures using R.
---

## Environment Setup and Installation
### 1. **R Environment**
- **Required Version:** R 4.0.0 or higher.
- **Required R Packages:**
  - ggplot2
  - dplyr
  - readxl
  - ComplexHeatmap
  - survival
  - survminer
- **Installation:**
  ```R
  install.packages(c("ggplot2", "dplyr", "readxl", "ComplexHeatmap","survival","survminer"))
  ```

### 2. **Python Environment**
- **Required Version:** Python 3.6 or higher.
- **Required Python Libraries:**
  - matplotlib
  - seaborn
  - pandas
  - numpy
- **Installation:**
  ```bash
  pip install pandas matplotlib seaborn numpy scipy
  ```

---

## Data Path

- The data files required for plotting are stored in the './data' directory."

- Example dataset:
  - `data/POEM/Clinical.xlsx`

---

## Script Descriptions

### 1. **`Survival_plot.Rmd`**
- **Type:** R Markdown file.
- **Recommended Environment**:RStudio
- **Average Run Time:** **Approximately 3 minute**.

### 2. **`Hi-secure_plot.ipynb`**
- **Type:** Jupyter Notebook file.
- **Recommended Environment:** Jupyter Notebook
- **Average Run Time:** **Approximately 5 minutes**.
---
## Steps to Run

1. Ensure that the necessary software and dependencies are installed.
2. Place the dataset in the specified `data/` folder.

---
