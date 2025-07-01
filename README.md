<b>🛡️ Healthcare Insurance Fraud Detection Using Machine Learning</b>
This project is aimed at building an intelligent and scalable system to detect fraudulent healthcare insurance claims using advanced machine learning techniques. It automates fraud identification, improves detection accuracy, and minimizes false positives in a real-world insurance claim dataset.

<b>📌 Project Overview:</b>
Fraudulent healthcare insurance claims lead to massive financial losses and reduced trust in the healthcare system. Traditional detection methods (manual auditing, rule-based systems) are time-consuming and ineffective against complex fraud patterns. This project leverages CatBoost and Isolation Forest models to detect fraud in claims data accurately and efficiently.

<h3>🎯 Objectives</h3>
<ul>
<li>Identify fraudulent health insurance claims using ML-based predictive models.</li>

<li>Minimize false positives and false negatives to avoid rejecting valid claims.</li>

<li>Automate the fraud detection pipeline to reduce manual effort.</li>

<li>Improve efficiency in claim processing and risk assessment.</li>
  
</ul>


<h3>🗂️ Dataset</h3>

The dataset includes:
<ul>

<li>Patient & Member Info: name, age, gender, location, employment, relationship.</li>

<li>Claim Details: cause of treatment, fee charged, number of dependents, membership duration.</li>

<li>Label: Indicates whether a claim is fraudulent (1) or legitimate (0).</li>
</ul>

<h3>🛠️ Tech Stack</h3>
<ul>
<li>Language: Python</li>

<li>ML Libraries: CatBoost, Scikit-learn, Isolation Forest, NumPy, Pandas</li>

<li>Visualization: Matplotlib, Seaborn</li>

<li>Tools: Google Colab, VS Code, Jupyter Notebook</li>
</ul>

<h3>🧠 Machine Learning Models</h3>

✅ CatBoost Classifier
<ol>
<li>Handles categorical data natively.</li>

<li>Excellent performance on classification tasks.</li>

<li>Final Accuracy: 93%, Precision (Fraud): 92%, Recall (Fraud): 95%</li>
</ol>

🚨 Isolation Forest
<ol>
<li>Unsupervised anomaly detection model.</li>

<li>Effective in catching rare fraud instances.</li>

<li>Accuracy: 89%</li>
</ol>

<h3>📊 Evaluation Metrics</h3>

![accuracy](https://github.com/user-attachments/assets/b0d65999-fad9-4c78-a5bb-09a571062e26)


<h3>📌 Future Enhancements</h3>
<ol>
  

<li>Integrate with a frontend UI for real-time claim entry and fraud scoring.</li>

<li>Add support for deep learning methods (e.g., LSTM for sequential claim behavior).</li>

<li>Real-time deployment via API for insurance providers.</li>

<li>Improve model interpretability using SHAP or LIME.</li>
</ol>


