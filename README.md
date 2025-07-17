# 🛒 Big Mart Sales Prediction using IBM watsonx.ai AutoAI

This project showcases how to use **IBM watsonx.ai AutoAI** to build an automated machine learning pipeline that predicts sales for Big Mart stores.  
With AutoAI, we can quickly experiment with multiple models, automatically engineer features, and optimize performance — all without writing complex ML code from scratch.

---

## 📦 Dataset

- **Dataset:** Big Mart Sales Prediction Dataset
- **Target variable:** `Item_Outlet_Sales` (total sales of each product per outlet)
- Contains features like:
  - `Item_Weight`
  - `Item_Fat_Content`
  - `Item_Visibility`
  - `Outlet_Identifier`
  - `Outlet_Location_Type`
  - etc.

*(Data source: public datasets, e.g., Kaggle — https://www.kaggle.com/datasets/shivan118/big-mart-sales-prediction-datasets)*

---

## 🧪 Workflow

1. Uploaded dataset to IBM watsonx.ai studio.
2. Created an **AutoAI experiment**, selecting `Item_Outlet_Sales` as the target.
3. AutoAI automatically:
   - Handled missing values
   - Engineered new features
   - Trained multiple pipelines using algorithms like XGBoost, LGBM, etc.
4. Evaluated models on validation data; selected best based on RMSE/R².
5. (Optional) Deployed the best model as an API.
6. Generated predictions on test data.

---

## ⚙️ Tools & Technologies

- 🧠 IBM watsonx.ai studio
- 🤖 AutoAI service
- 📊 Python (for optional EDA and evaluation)
- 📂 CSV dataset files

---

## 📊 Results

| Metric      | Score (example) |
|------------:|----------------:|
| R² (Validation) | 0.601 |
| RMSE         | 1067.382 |

---

## 🖼 Screenshots

| Step | Screenshot |
|-----|-----------:|
| Dataset Upload | ![](screenshots/dataset_upload.png) |
| AutoAI Experiment Setup | ![](screenshots/experiment_setup.png) |
| Leaderboard of Pipelines | ![](screenshots/leaderboard.png) |
| Pipeline Visualization | ![](screenshots/pipeline_visualization.png) |
| Deployment Step | ![](screenshots/deployment.png) |

*(Store your images inside a `/screenshots` folder in your repo.)*

---

## ✨ What I Learned

- Automating the ML pipeline creation with AutoAI
- Comparing multiple models and metrics
- Visualizing and understanding AutoAI pipelines
- Deploying models as APIs on watsonx.ai

---

## 🚀 Future Work

- Manual feature engineering to compare with AutoAI
- Additional hyperparameter tuning
- Combine multiple top pipelines into an ensemble
- Add a detailed EDA notebook

---

