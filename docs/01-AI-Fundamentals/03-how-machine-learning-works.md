# How Machine Learning Works

## Learning Objectives

By the end of this chapter, you will understand:

- The Machine Learning lifecycle.
- How a model is trained.
- The importance of data.
- How predictions are made.

---

# Machine Learning Workflow

A Machine Learning system follows a series of steps to learn from data and make predictions.

```mermaid
flowchart LR
    A[Collect Data] --> B[Prepare Data]
    B --> C[Choose Algorithm]
    C --> D[Train Model]
    D --> E[Test & Evaluate]
    E --> F[Deploy Model]
    F --> G[Prediction]
```

---

# Step 1 — Collect Data

Every Machine Learning project begins with collecting data.

Examples:

- Customer information
- Images
- Videos
- Sensor data
- Transaction history
- Website activity

The quality of the data directly impacts the quality of the model.

---

# Step 2 — Prepare the Data

Raw data usually contains:

- Missing values
- Duplicate records
- Incorrect values
- Noise

Before training, the data must be cleaned and organized.

This process is called **Data Preprocessing**.

---

# Step 3 — Choose a Machine Learning Algorithm

The algorithm depends on the business problem.

Examples include:

- Classification
- Regression
- Clustering
- Recommendation

Different problems require different algorithms.

---

# Step 4 — Train the Model

During training:

- The algorithm studies historical data.
- It learns relationships and patterns.
- It creates a trained model.

The trained model stores what it has learned from the data.

---

# Step 5 — Test and Evaluate

The trained model is tested using data it has never seen before.

The goal is to measure how accurately it performs.

If the performance is poor, the model may need:

- More data
- Better features
- A different algorithm

---

# Step 6 — Make Predictions

Once deployed, the trained model can make predictions on new data.

Examples include:

- Spam detection
- Product recommendations
- Fraud detection
- Image classification

---

# Complete Machine Learning Pipeline

```text
Collect Data
      ↓
Prepare Data
      ↓
Choose Algorithm
      ↓
Train Model
      ↓
Evaluate Model
      ↓
Deploy Model
      ↓
Prediction
```

---

# Key Points

- Good data produces better models.
- Training allows the algorithm to learn patterns.
- Evaluation measures model performance.
- The trained model is used to make predictions.

---

# Quick Revision

- What is the first step in Machine Learning?
- Why is data preprocessing important?
- What happens during model training?
- Why do we evaluate a model?

---

# Summary

Machine Learning follows a structured workflow, beginning with collecting data and ending with predictions. Every stage plays an important role in building an accurate and reliable Machine Learning model.

---

## Next Topic

➡️ Types of Machine Learning
