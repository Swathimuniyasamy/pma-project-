
---

## 🧠 Project Overview

This project includes a complete end-to-end data science pipeline, consisting of the following components:

- **Data Import:** Reads data from external sources such as CSV, Excel, or databases.
- **Data Preparation:**
  - Cleansing
  - Feature selection
  - Derived variables
- **Model Training:**
  - Uses one or more predictive modeling nodes (e.g., Decision Tree, Neural Network, Logistic Regression).
- **Model Evaluation:**
  - ROC Curve
  - Confusion Matrix
  - Gains Chart
- **Deployment:**
  - Outputs predictions or model scoring for new data

---

## 🛠️ Requirements

- **IBM SPSS Modeler v18.0** or later
- Data files used in the stream (may be in the `data/` directory or need to be reconnected)

---

## 🚀 How to Run the Project

1. Open **IBM SPSS Modeler**.
2. Go to `File → Open Stream`, and select `PmaProject.str`.
3. Review the stream layout and reconnect any broken data source nodes.
4. Run the stream by clicking the **Run** icon or pressing `F5`.
5. View results through the **output**, **evaluation**, or **table** nodes.

---

## 📈 Output

- Predictions
- Model evaluation metrics (Accuracy, AUC, etc.)
- Exported data (if included in the stream)

---

## 👤 Author

- **Created by:** swathi
- **Last Modified:** April 25, 2025

---

## 📌 Notes

- Ensure all required data sources are available and correctly linked.
- If the `.str` file fails to open, rename it to `.zip` and extract to inspect contents.
