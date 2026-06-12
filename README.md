Clinical Dermatological Data Analysis & Cancer Risk Assessment
Executive Summary
This project involves Exploratory Data Analysis (EDA) on a specialized dermatological dataset comprising 10,000 patient records. The objective is to identify demographic trends, physical symptoms, and genetic risk factors associated with skin cancer to support data-driven diagnostic evaluations.
Technical Stack
Programming Language: Python
Data Manipulation: Pandas, NumPy
Data Visualization: Seaborn, Matplotlib
Environment: Jupyter Notebook
Methodology
1.Data Ingestion & Profiling:
Imported a clinical dataset containing 14 specific diagnostic features, including Age, Gender, Skin Type, Sun Exposure, Family History, Mole Count, Asymmetry, Border Irregularity, and Skin Cancer status.
Evaluated dataset dimensions and data types to ensure readiness for statistical manipulation.
2.Statistical Summary:
Computed descriptive statistics to establish the central tendencies and dispersion metrics for key numerical indicators, such as Lesion Diameter (mm) and Mole Count (ranging from 0 to 14).
3.Data Segmentation:
Executed strategic data filtering using Pandas to isolate high-risk patient profiles, such as slicing the data by specific Genders and isolating patients with a documented Family History of dermatological issues.
4.Visual Analytics:
Engineered visual models using Seaborn, including bar plots to compare Skin Cancer incidence rates across different Genders, and scatter plots to map Age against Skin Cancer occurrence.
Repository Contents
The core Jupyter Notebook containing all Python code, data segmentation logic, and statistical outputs.
<img width="482" height="286" alt="Screenshot 2026-06-12 070604" src="https://github.com/user-attachments/assets/17946b97-930e-4049-86da-740d432f6598" />

Exported visualization demonstrating the demographic distribution of skin cancer rates. 
<img width="469" height="348" alt="Screenshot 2026-06-12 070620" src="https://github.com/user-attachments/assets/e69ebb62-d1e6-48ee-b5e4-e16c35b04066" />

Exported visualization highlighting demographic age clusters and their correlation to malignant diagnoses. 
Conclusion
The analysis successfully isolates critical risk factors—both genetic and physical—and visualizes their impact on skin cancer incidence rates. This data-driven approach highlights the strongest predictors of malignancy and provides a solid foundation for advanced healthcare diagnostics.
