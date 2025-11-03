# Remote_Work_Health_Impact_EDA
Exploratory Data Analysis on the mental and physical health effects of remote work post-pandemic
This project conducts an Exploratory Data Analysis (EDA) on survey data collected in 2025 to investigate how different work arrangements (Remote, Hybrid, Onsite) affect employees' mental and physical well-being.

1. Research Goal
The primary objective is to identify patterns, correlations, and key risk factors related to Burnout, Social Isolation, and Work-Life Balance among a global workforce following the shift to flexible work models.

2. Data Integrity and Cleaning
The data was validated to ensure reliability for statistical modeling:
Cleanliness: No significant outliers were detected in key numerical variables (Age, Work Hours, Scores), confirming the data's consistency.
Missing Data: The highest missing ratio was found in the Mental_Health_Status column (25.31%). All missing values were imputed using the Mode method to preserve the dataset integrity, making it ready for analysis

3. Key Findings & Insights
The analysis revealed a selective impact of flexible work on employee health:
Finding 1: Social Isolation is the Primary Remote Risk
Work-Life Balance (WLB): The type of work arrangement (Remote, Hybrid, Onsite) did not create a significant difference in average WLB scores.

Social Isolation: Remote employees reported significantly higher social isolation scores compared to Onsite employees. This indicates physical distance is the main psychological challenge, not WLB.

Correlation: A strong relationship exists between increased Burnout and increased Social Isolation, confirming that lack of social support fuels burnout risk.

 Finding 2: Burnout is Concentrated in Mid-Career
Distribution: The highest rate of Medium and High Burnout is concentrated in the 26–45 age group.

Implication: This cohort, often managing career growth and family responsibilities, is the most vulnerable group requiring targeted support.

 Finding 3: Common Physical Risks
Ergonomics: The highest reported physical issues across all groups were Back Pain and Eye Strain.
Remote Specific: Neck and Wrist Pain rates were slightly higher for remote employees, indicating inadequate home office ergonomics.

4. Strategic Recommendations
Interventions must be targeted based on these findings:
Targeted Social Support: Implement Systematic Training to Increase Mental Health Awareness and promote supportive leadership to reduce isolation among Remote staff.
Age-Specific Burnout Programs: Focus stress management workshops and coaching on the high-risk 26–45 age group to manage professional boundaries.
Ergonomics: Sustain Physical Health and Ergonomics Programs, including training on the 20-20-20 rule and proper posture, particularly for Hybrid and Remote workers.

5.  Technologies & Libraries

This project uses the following key libraries, which can be installed via pip:
* **Pandas:** For data loading, manipulation, and statistical processing.
* **NumPy:** For numerical operations.
* **Matplotlib / Seaborn:** For data visualization (Box plots, Bar charts, Heatmaps).
* **Missingno:** For missing data visualization.
* **Seaborn**

*  6.  How to Run the Project

To replicate this analysis:
1.  **Clone the Repository:** Download the project files (including the `.ipynb` and `.csv` files) to your local machine.
    ```bash
    git clone [Your Repository URL Here]
    ```
2.  **Install Dependencies:** Ensure you have the required Python libraries installed in your environment.
    ```bash
    pip install pandas numpy matplotlib seaborn missingno
    ```
3.  **Open Jupyter:** Launch Jupyter Notebook or Jupyter Lab.
    ```bash
    jupyter notebook
    ```
4.  **Execute:** Open the `Remote_Work_Health_EDA.ipynb` file and run all cells sequentially.



