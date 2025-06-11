# 📊 Informative Statistics Health Analysis

This repository presents a structured statistical analysis pipeline for a health-related study, performed using **R** within a **Jupyter Notebook** environment. The analysis aims to explore relationships among clinical or behavioral variables, using cleaned spreadsheet and `.rds` data.

## 📁 Repository Structure

informative-stats-health-analysis/
├── data/
│ ├── combined.xlsx # Raw or cleaned spreadsheet data
│ ├── processed_data.rds # RDS-formatted dataset for R
│ └── README.md # Description of data sources and structure
│
├── notebooks/
│ └── analysis_inf_stats.ipynb # Main R-based Jupyter Notebook
│
├── reports/
│ └── statistical_analysis_summary.docx # Final report of findings
│
├── docs/
│ ├── study_details.docx # Background and design of the study
│ ├── step_by_step_procedure.docx # Guide to analytical steps
│ └── abstract_symposium.pdf # Related abstract or publication
│
├── LICENSE
├── .gitignore
└── README.md


---

## 🧪 Analysis Overview

- **Tools Used**:  
  - R (via IRkernel in Jupyter)  
  - Libraries: `tidyverse`, `readxl`, `psych`, `ggplot2`, etc.

- **Key Steps**:
  - Import and preprocessing of `.xlsx` and `.rds` data
  - Descriptive statistics (mean, SD, frequency counts)
  - Group comparisons, correlations, and cross-tabulations
  - Visualizations for key trends
  - Summary table generation for reporting

---

## 🔧 How to Run

1. Install the necessary R packages (if not already):
   ```r
   install.packages(c("tidyverse", "readxl", "psych", "ggplot2"))


---

## 🧪 Analysis Overview

- **Tools Used**:  
  - R (via IRkernel in Jupyter)  
  - Libraries: `tidyverse`, `readxl`, `psych`, `ggplot2`, etc.

- **Key Steps**:
  - Import and preprocessing of `.xlsx` and `.rds` data
  - Descriptive statistics (mean, SD, frequency counts)
  - Group comparisons, correlations, and cross-tabulations
  - Visualizations for key trends
  - Summary table generation for reporting

---

## 🔧 How to Run

1. Install the necessary R packages (if not already):
   ```r
   install.packages(c("tidyverse", "readxl", "psych", "ggplot2"))

Launch Jupyter Notebook using the R kernel:
jupyter notebook

Open and run the notebook:
notebooks/analysis_inf_stats.ipynb

#Reporting
The main findings are presented in:

reports/statistical_analysis_summary.docx: final formatted report

notebooks/analysis_inf_stats.ipynb: reproducible analysis steps

Supporting documents (e.g., abstract, procedures, and methodology) are located in the docs/ directory.


#Tools used: 

R, Jupyter, and open-source statistical libraries.


