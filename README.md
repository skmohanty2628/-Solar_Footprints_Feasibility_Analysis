🌞 Solar Footprints Feasibility Analysis in California

As part of my ISM 6562 – Big Data Applications Final Project at the University of South Florida, I contributed to a group effort analyzing the feasibility of solar power installations in California using big data and machine learning techniques. The project leveraged Apache Spark on Databricks for large-scale data processing and predictive modeling.

🔑 My Contributions

Data Preprocessing & Cleaning:

Used PySpark to handle a large dataset (~millions of rows) with geographic and infrastructure features (land area, proximity to substations, installation type, rural/urban classification).

Dealt with missing values, normalized continuous variables, and transformed categorical columns for ML compatibility.

Feature Engineering:

Focused on high-impact predictors such as distance to substations, land availability (acres), and urban vs. rural classification to determine site feasibility.

Generated derived features for infrastructure proximity and resource accessibility.

Machine Learning Modeling:

Implemented classification models in Spark MLlib to predict whether a given site is feasible or non-feasible for solar installation.

Applied logistic regression and decision tree classifiers, tuning hyperparameters for balanced accuracy and interpretability.

Visualization & Insights:

Created data visualizations in SparkSQL + matplotlib/Seaborn to highlight feasible vs. non-feasible regions.

Demonstrated how certain counties and land types correlate strongly with higher feasibility scores.

Business & Policy Relevance:

Showcased how utility companies, policymakers, and investors can leverage big data analytics to identify optimal solar project sites, minimizing risks and maximizing renewable energy ROI.

Connected findings with California’s broader clean energy transition goals.

📊 Key Outcomes

Identified critical geographic and technical drivers for solar site feasibility.

Built scalable ML pipelines to analyze large geospatial datasets.

Highlighted cost-saving opportunities by avoiding investments in non-feasible regions.

Provided a framework for replicating renewable energy feasibility studies in other states or countries.

👥 Project Team

Gaurav Vinayak Yadav

Subham Mohanty

Umeaiman Yusuf Merchant

Yash Ajay Chauhan

📄 Project Presentation ( https://usfedu-my.sharepoint.com/:v:/g/personal/yadavg_usf_edu/EXwbC7wvSo5LiaU6Obk_kYQByXWKDb_7grCEV3q8PBTyQw?e=SVrFWQ)
