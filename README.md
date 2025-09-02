# Clustering Countries using Supervised Learning K-Means on Development Indicators-
This project explores how nations can be grouped based on multiple dimensions of development rather than a single indicator like GDP. Using World Bank Development Indicators (2018–2020), the study applies data preprocessing, standardization, and K-Means clustering to segment 15 countries into meaningful groups.

Contents

- DevelopmentIndicators_DataMining.docx – Full project report documenting methodology, results, visualizations, and insights.

- DevelopmentIndicators_DM_codes.ipynb – Google Colab Notebook containing data fetching (via wbgapi), preprocessing, cleaning, and standardization.

- DataMining_Kmeansclustering_DevelopmentIndicators.ows – Orange Data Mining workflow file used to run and visualize the K-Means clustering process.

Methodology

- Data Source – World Bank Development Indicators (GDP, Life Expectancy, Primary School Enrollment, Secure Internet Servers).

- Preprocessing – Cleaning missing values, reshaping data, standardizing with RobustScaler.

- Clustering – Applied K-Means (k=4) using Orange Data Mining and validated with PCA plots, scatter plots, and geographic maps.

Findings –

- C1 – Major Emerging Economies (Brazil, China, India, etc.)

- C2 – The Economic Superpower (USA)

- C3 – Unique Developing Profile (Nigeria)

- C4 – Advanced High-Tech Economies (Germany, Japan, Singapore, Australia)

Key Insights

- GDP alone fails to capture true development differences.

- A multi-dimensional clustering approach highlights nuanced profiles of countries.

- The method separates the USA as a unique cluster and reveals distinct tiers of emerging vs. advanced economies.
