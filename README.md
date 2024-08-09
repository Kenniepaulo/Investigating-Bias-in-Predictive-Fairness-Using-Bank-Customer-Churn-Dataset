This project examines the ethical challenges of using artificial intelligence (AI) in customer churn prediction within the retail banking sector, specifically focusing on gender bias. By ensuring that predictive models are both accurate and fair, the project aims to address the potential for AI to perpetuate societal biases.

Motivation
In the banking industry, predicting customer churn is essential for retaining customers, as the cost of acquiring new customers is often higher than retaining existing ones. While AI has significantly enhanced the accuracy of these predictions, the complexity of AI models—often referred to as "black-box" systems—raises concerns about their fairness and transparency. This project addresses these concerns by analyzing the fairness of churn prediction models, particularly in terms of gender bias.

Data and Methodology

Dataset: The project utilizes a retail bank's CHURN dataset, which includes various customer demographics, account details, and churn status.
Preprocessing: The data was prepared using outlier detection (IQR method), winsorization to handle extreme values, and one-hot encoding for categorical variables.
Exploratory Data Analysis (EDA): EDA involved visualizations such as histograms, violin plots, and scatter plots to identify factors influencing churn, with a specific focus on gender disparities.
Modeling: A Support Vector Machine (SVM) with an RBF kernel was chosen due to its capability to manage non-linear relationships. The model was trained using balanced class weights to address class imbalances.
Evaluation: The model's performance was assessed using metrics like accuracy, precision, recall, and F1-score. To evaluate fairness, metrics such as Equal Accuracy, Demographic Parity, and Equal Opportunity were applied, comparing the model’s outcomes across gender groups.
Key Findings
The analysis revealed a notable gender bias, with the model predicting churn more frequently and less accurately for female customers compared to males. This finding highlights the necessity of refining AI models to ensure equitable outcomes across different demographic groups.

Conclusion
This project emphasizes the need for fairness in AI-driven decision-making in the banking sector. By addressing and mitigating gender bias, the reliability and ethical integrity of predictive models can be significantly improved. Future work will focus on refining these models to better represent diverse customer behaviors without perpetuating unfair biases.
