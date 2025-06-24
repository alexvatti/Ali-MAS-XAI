# Ali-MAS-XAI

**Phase-01:  Model Development**

1. Created datasets for **Top 10, 20, 30, 40, 50 Web Service Categories**.
2. Cleaned and preprocessed the data (stopwords removal, label encoding).
3. Extracted features using **TF-IDF** and **SBERT embeddings**.
4. Trained ML models **(LogReg, Random Forest, XGBoost)** and a Deep Learning model **(BI-LSTM)**.
5. Evaluated using **Accuracy, Precision, Recall, and F1-Score**.


**Phase-02: Enhanced Model Development**

1. Merged and balanced datasets across **Top 50 Web Service Categories** to ensure **uniform class distribution**.
2. Cleaned and  preprocessing (cleaning, label encoding) to align with the merged structure.
3. Extracted features using **TF-IDF** and **SBERT embeddings** on the updated dataset.
4. Trained models: **Logistic Regression**, **Random Forest**, **XGBoost**, and **BI-LSTM**.
5. Evaluated using **Accuracy**, **Precision**, **Recall**, and **F1-Score** to benchmark improvements.



**Phase-03: Advanced Model Optimization with Transformers**

1. Leveraged the preprocessed and balanced dataset from **Phase-02** for advanced transformer-based modeling.
2. Integrated **BEaRT-RoBERTa** and **DeepSeek** transformer models for deeper semantic understanding and improved generalization.
3. Applied **fine-tuning** on the labeled dataset using transformer-specific training pipelines with early stopping and learning rate schedulers.
4. Evaluated model performance using **Accuracy**, **Precision**, **Recall**, and **F1-Score**, achieving consistent scores of **90% and above** across all metrics.
5. Benchmarked results against Phase-02 models to confirm **significant improvement in contextual classification performance**.


