# Customer Purchase Behavior Analysis Engine

An advanced final-year Data Analytics project utilizing an automated data engineering and exploratory data analysis (EDA) pipeline built entirely in the Python ecosystem. This application ingests transaction logs, applies robust data-cleaning workflows, handles statistical data imputation, filters extreme anomalies, and renders multi-dimensional consumer behavioral charts.

## 📊 Project Overview
* **Topic:** Customer Purchase Behavior Analysis Using Exploratory Data Analytics and Visualization Techniques
* **Academic Level:** Master of Computer Application (MCA) - Final Year Project
* **Core Focus:** Automated ETL Pipelines, Data Preprocessing, Feature Analysis, and Business Intelligence Reporting

---

## 🛠️ Tech Stack & Dependencies
The development environment operates on the core Python data science stack. To run the project locally, install the following libraries:

```bash
pip install pandas numpy matplotlib seaborn
Pandas: Structured data manipulation using DataFrame utilities.

NumPy: Vectorized matrix math operations and statistical threshold tracking.

Matplotlib: Core graphical engine for layout management and rendering canvas plots.

Seaborn: High-level statistical visualization layer for rendering density plots and heatmaps.

🚀 Repository File Structure
Ensure your workspace directory matches the following layout for seamless compilation:

====================================================================================================
├── Customer_Behavior_Analysis.ipynb     # Interactive Jupyter Notebook (Cell-by-Cell Core Code)
├── simulated_retail_transactions.csv    # Generated evaluation transaction database
└── README.md                            # Main project layout documentation index
====================================================================================================

⚙️ Modular Pipeline Flow Breakdown
1. Data Ingestion & Structural Normalization
Reads raw transactional log variables dynamically.

Enforces structural string formatting (snake_case column titles) to ensure consistency across variable queries.

Casts chronological tracking entries safely into Pandas datetime array objects.

2. Missing Value & Null Record Imputation
Scans incoming feature matrices for empty cells (NaN indicators).

Automatically fills missing indices using data-driven median imputation formulas to keep datasets mathematically objective.

3. Outlier Mitigation Framework
Prunes data entry errors or exceptional extreme purchasing anomalies using the Interquartile Range (IQR) filtering method:

IQR=Q3−Q1
Establishes dynamic analytical boundaries using lower and upper mathematical fences:

Lower Fence=Q1−1.5×IQR
Upper Fence=Q3+1.5×IQR
4. Graphic Visualization Canvas Engine
Generates live visual outputs divided into structural dashboard panels to help business stakeholders mine strategic insights:

Demographic Profiles: Multi-variable density histograms identifying primary age spans and target middle-class income brackets.

Correlation Heatmaps: Color-coded linear dependency matrix displays utilizing Pearson Correlation coefficients.

Commercial Performance Charts: Sorted categorical bar charts assessing revenue shares, showing major product demand distribution.

Gateway Utilization Analysis: Percentage pie chart metrics detailing checkout trends across modern payment platforms.

🏃‍♂️ Execution Guide
Launch your command terminal in your workspace folder and open the notebook application using jupyter notebook.

Open Customer_Behavior_Analysis.ipynb.

Execute the notebook cells sequentially (Cell 1 to Cell 7). The synthetic data layer will execute automatically, load the dataset file, clean data frames, and render your analytical dashboard directly onto your screen.
