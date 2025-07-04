# Kiva Loan Impact Analysis

This project analyzes Kiva microloan data to identify which combinations of borrower country and loan sector are associated with the highest repayment impact, using statistical modeling and visualization in R.

---

## 📂 Repository Structure

Kiva-Loan-Impact-Analysis/
├── analysis/ # R scripts (.Rmd)
├── report/ # Project proposal/report (PDF)
├── figures/ # Output images (created locally)
├── output/ # Result tables (created locally)
├── data/ # [Not included] Users must create this folder locally for data
├── README.md
└── .gitignore


---

## 🚀 How to Reproduce This Analysis

1. **Prepare the Data**
   - Download the dataset `big_table.csv` (not provided here).
   - Create a folder called `data/` locally and place the file inside.

2. **Install Required Packages**
   In R:
   ```r
   install.packages(c("dplyr", "ggplot2", "data.table", "lubridate", "patchwork", "reshape2"))

3. **Run the Analysis**
  In R:
  rmarkdown::render("analysis/project_final.Rmd")

4. **Reproducibility Notes**
  The analysis is fully reproducible if you change this line:
  loans <- fread("/Users/danielkravtsov/Desktop/2nd_year/הנדסת נתונים/kivadata_org/big_table.csv")
  to the data in your machine.
  The dataset (big_table.csv) is not included in this repository.
