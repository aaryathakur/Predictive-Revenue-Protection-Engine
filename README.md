# 🚀 Enterprise Customer Retention Engine & Predictive Revenue Protection

## 1. Project Overview
This project delivers a **Production-Ready AI Churn Service** designed to identify at-risk customers and quantify potential revenue leakage. Using the Telco Customer Churn dataset, the engine moves beyond simple accuracy to focus on **Business ROI** and **Strategic Intervention**.

**Phase 1 Focus:** Building a robust, scalable, and interpretable predictive pipeline that serves as the foundation for Explainable AI (Phase 2) and GenAI-driven retention (Phase 3).

---

## 2. Strategic Objectives
* **Predictive Intelligence:** Training high-performance models to detect churn signals before attrition occurs.
* **Imbalance Management:** Utilizing specialized metrics and weighted algorithms to handle the minority churn class effectively.
* **Revenue Protection:** Translating model recall into a dollar-value impact for executive stakeholders.
* **Deployment Readiness:** Ensuring sub-10ms inference latency for real-time integration with CRM systems.

---

## 3. The Tech Stack & Architecture
* **Language:** Python 3.13 (Miniconda Environment)
* **Core Libraries:** Pandas, NumPy, Scikit-Learn, XGBoost
* **Evaluation Engine:** Matplotlib, Seaborn for business-centric visualizations
* **Pipeline:** Scikit-Learn `Pipeline` & `ColumnTransformer` for seamless production deployment

---

## 4. Key Features & Engineering
To boost the model's predictive power, the following **Business Logic Features** were engineered:
* **Charge Velocity:** Ratio of Total Charges to Tenure to detect sudden billing spikes.
* **Service Density:** Count of active services to measure customer "stickiness."
* **Contract Segmentation:** Categorizing customers into New, Junior, and Loyal segments for targeted analysis.

---

## 5. Model Benchmarking & Performance
We evaluated multiple architectures using **Stratified K-Fold Cross-Validation** to ensure stability:

| Metric | Logistic Regression | XGBoost |
| :--- | :--- | :--- |
| **PR-AUC (Primary)** | 0.65+ | 0.63+ |
| **Recall (Churners)** | 80% | 74% |
| **Latency** | ~1.2ms | ~8.5ms |

**Final Selection:** *Logistic Regression (Balanced)* was chosen for Phase 1 due to its superior PR-AUC, high recall, and perfect interpretability for consulting stakeholders.

---

## 6. Strategic Business Impact
Unlike standard ML projects, this engine calculates **Revenue ROI**:
* **Monthly Revenue Protected:** Estimated **$XX,XXX** (based on 30% successful retention of detected churners).
* **Top Churn Drivers:** Identified **Month-to-Month Contracts** and **Fiber Optic Service** as the highest friction points requiring immediate policy intervention.

---

## 7. Roadmap: The Path to Advanced AI
* ✅ **Phase 1:** Production Model & ROI Analysis (Completed)
* ⏳ **Phase 2 (Explainable AI):** Integrating SHAP to provide "Why" insights for every individual prediction.
* ⏳ **Phase 3 (GenAI Engine):** Leveraging LLMs to generate personalized retention email scripts based on model output.
* ⏳ **Phase 4 (MLOps):** Real-time monitoring for model drift and automated retraining.

---

## 8. How to Run
1. Clone the repository.
2. Ensure the dataset `WA_Fn-UseC_-Telco-Customer-Churn.csv` is in the root directory.
3. Run the Jupyter Notebook `code.ipynb`.
