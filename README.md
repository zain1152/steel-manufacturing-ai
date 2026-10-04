# 🏭 Steel Manufacturing AI System

### Quality Inspection • Predictive Maintenance • Explainable AI

An end-to-end **Artificial Intelligence and Machine Learning project for steel manufacturing**, combining **quality inspection, predictive maintenance, and Explainable AI (XAI)**.

The project demonstrates how machine learning can be applied to manufacturing data to:

* Predict whether a steel product passes or fails quality inspection
* Identify important process and material factors affecting quality
* Estimate machine failure risk
* Identify machines requiring maintenance attention
* Explain model predictions using **SHAP**
* Generate engineering-oriented recommendations from model outputs

---

## 📌 Project Overview

Manufacturing plants generate large amounts of process, machine, material, and inspection data.

The objective of this project is to demonstrate how this data can be transformed into an AI-based decision-support system for a steel manufacturing environment.

The system contains two major machine learning components:

```text
                    STEEL MANUFACTURING DATA
                              │
                ┌─────────────┴─────────────┐
                │                           │
                ▼                           ▼
        QUALITY INSPECTION          PREDICTIVE MAINTENANCE
                │                           │
                ▼                           ▼
          Pass / Fail                 Failure Risk
                │                           │
                ▼                           ▼
              SHAP                        SHAP
                │                           │
                └─────────────┬─────────────┘
                              ▼
                    ENGINEERING INSIGHTS
                    & RECOMMENDATIONS
```

---

## 🎯 Project Objectives

### Quality Inspection

Build machine learning models capable of predicting whether a manufactured steel product will:

* ✅ Pass quality inspection
* ❌ Fail quality inspection

The quality system also investigates the factors contributing to failure predictions.

### Predictive Maintenance

Use machine-condition and maintenance-related variables to estimate machine failure risk and prioritize maintenance activities.

### Explainable AI

Use **SHAP (SHapley Additive exPlanations)** to understand which features contribute most strongly to individual predictions and overall model behavior.

---

## 📊 Dataset

The project uses a manufacturing dataset containing:

* **10,000 observations**
* **32 original features**
* Multiple material, process, machine, and maintenance variables
* Categorical and numerical features
* Production and inspection information

### Main Variables

#### Material Properties

* Carbon
* Manganese
* Silicon
* Sulfur
* Phosphorus
* Hardness
* Tensile Strength
* Yield Strength
* Thickness
* Width

#### Manufacturing Process

* Air Temperature
* Furnace Temperature
* Cooling Rate
* Rolling Speed
* Pressure
* Inspection Time

#### Machine Condition

* Vibration
* Current
* Voltage
* Power
* Tool Wear
* Lubricant Level
* Humidity

#### Maintenance History

* Days Since Maintenance
* Previous Failure Count
* Machine ID
* Operator ID
* Shift

#### Quality Information

* Defect Type
* Pass / Fail

---

# 🔬 Part 1 —
