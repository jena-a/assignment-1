Understanding Risk Factors in Asthma

This project aims to analyse a comprehensive dataset of factors that may influence the development and severity of asthma within this population.

Asthma is a chronic respiratory condition that affects millions globally. It leads to significant healthcare costs, including hospital visits, medication, and lost productivity. Understanding the risk factors contributing to asthma is crucial for improving prevention strategies, clinical management, and public health interventions.

Dataset Content

The Asthma Disease Dataset is publicly available on Kaggle.
	•	It contains 2,393 rows (i.e., patients) and 29 columns (i.e., variables).
	•	Variables can be broadly divided into:
Descriptors: age; sex; ethnicity; body-mass index (BMI)
Environmental factors: smoking; air pollution exposure; household conditions; physical activity
Medical history: prior respiratory infections; comorbidities
Family history: asthma; allergies
Symptoms and outcomes: FEV1; FVC; asthma diagnosis; severity scores

Business Requirements

The primary goal is to gain a deeper understanding of the risk factors associated with asthma. Insights from this analysis can guide healthcare providers, policymakers, and researchers to improve early detection, preventive strategies, and patient management.

Questions, Hypotheses, and Validation

Questions:
	•	Which factors are most strongly associated with asthma prevalence and severity?
	•	Are certain environmental exposures or lifestyle factors protective against asthma?

Hypotheses:
	1.	Higher BMI and exposure to air pollutants increase the risk of asthma.
Validation: scatter plots and correlation analysis grouped by asthma diagnosis.
	2.	Regular physical activity is protective against asthma.
Validation: KDE plots comparing active vs. inactive individuals.
	3.	Family history of asthma is associated with earlier onset of symptoms.
Validation: box plots grouped by family history using Plotly.

Project Plan
	•	Data Acquisition and ETL: Pandas, Feature-engine
	•	Exploratory Analysis and Visualisation: Matplotlib, Seaborn
	•	Hypothesis Testing and Deeper Analysis: Seaborn
	•	A new CSV file will be created at the end of ETL for downstream analysis
	•	Visualisation choices: histograms for numeric variables; box plots for numeric variables grouped by BMI category; count plots for categorical variables; correlation heatmap for numeric variables; scatter plots for exploring relationships between numeric variables

The rationale is to map business requirements to visualisation outputs, providing actionable insights for stakeholders.

Analysis Techniques

Data was imported from a CSV, inspected for quality, and transformed for analysis. Basic visualisations guided ETL decisions. Hypotheses were tested using Seaborn visualisations. The ETL process structured the workflow from initial cleaning to final analysis.

Ethical Considerations

No ethical concerns are present, as the dataset is fully anonymised.

Development Roadmap

Familiarity with ETL and analysis code improved over the course of the project. Initial exploration helped refine feature engineering and visualisation strategies.

Main Data Analysis Libraries
	•	Numpy – numerical operations
	•	Pandas – data manipulation and cleaning
	•	Matplotlib – static visualisations
	•	Seaborn – statistical visualisations

Credits
	•	Asthma dataset provided by Kaggle
	•	Code generation and debugging assisted by ChatGPT and GitHub Co-Pilot