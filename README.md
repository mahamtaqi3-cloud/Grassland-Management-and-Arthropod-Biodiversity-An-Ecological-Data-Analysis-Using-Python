# 🌱 Grassland Management and Arthropod Biodiversity

### *An Ecological Data Analysis and Machine Learning Project Using Python*
---

## 📖 Overview

Grassland ecosystems support a remarkable diversity of insects, playing a crucial role in ecosystem functioning and food web stability. However, agricultural management practices such as **fertilization, grazing, and mowing** can influence these communities in different ways.

This project analyzes a real ecological dataset to investigate how grassland management affects **arthropod biodiversity**, with a particular focus on **herbivore species richness**. In addition to exploratory data analysis, a **Random Forest Regression** model was developed to assess the predictive importance of environmental variables.

---

## 🎯 Objectives

* Explore patterns in grassland management practices.
* Examine relationships between management intensity and herbivore biodiversity.
* Investigate ecological interactions between plants and arthropods.
* Visualize biodiversity trends using Python.
* Build a machine learning model to predict herbivore species richness.
* Identify the most influential environmental variables.

---

## 📂 Dataset

**Source:** Dryad Digital Repository

**Dataset Used:** `04_SEMData_2009.xlsx`

The dataset contains ecological observations collected from grassland plots, including management practices, plant diversity, and arthropod communities.

### Variables

| Variable                  | Description                      |
| ------------------------- | -------------------------------- |
| PlotID                    | Grassland plot identifier        |
| Region                    | Study region                     |
| Fertilization             | Fertilizer application intensity |
| Grazing                   | Grazing intensity                |
| Mowing                    | Mowing intensity                 |
| Time_after_mowing         | Time elapsed after mowing        |
| Plant_SpeciesRichness     | Number of plant species          |
| Plant_biomass             | Plant biomass                    |
| Herbivore_SpeciesRichness | Number of herbivore species      |
| Predator_SpeciesRichness  | Number of predator species       |
| Herbivore_biomass         | Herbivore biomass                |
| Predator_biomass          | Predator biomass                 |

---

# 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# 📊 Project Workflow

```
Load Dataset
      │
      ▼
Data Exploration
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Correlation Analysis
      │
      ▼
Machine Learning
(Random Forest Regression)
      │
      ▼
Feature Importance Analysis
      │
      ▼
Biological Interpretation
```

---

# 📈 Exploratory Data Analysis

The project investigated several ecological questions:

* 🌿 Does fertilization influence herbivore species richness?
* 🐄 Does grazing intensity affect herbivore diversity?
* 🌾 Does mowing reduce herbivore richness?
* 🌱 Does plant species richness support greater herbivore diversity?
* 🕷️ Are predator communities associated with herbivore communities?

---

# 🤖 Machine Learning

A **Random Forest Regressor** was trained to predict **Herbivore Species Richness** using environmental and management variables.

### Features

* Fertilization
* Grazing
* Mowing
* Time after mowing
* Plant species richness
* Plant biomass

### Target

* Herbivore Species Richness

---

# 📌 Model Performance

| Metric                         |     Score |
| ------------------------------ | --------: |
| Mean Absolute Error (MAE)      |  **6.37** |
| Root Mean Squared Error (RMSE) |  **7.63** |
| R² Score                       | **-0.09** |

Although the predictive performance was limited, the results highlight the complexity of ecological systems and suggest that additional environmental variables may be required to accurately predict herbivore diversity.

---

# 📷 Visualizations

The notebook includes:

* 📊 Distribution of ecological variables
* 🌿 Fertilization vs Herbivore Species Richness
* 🐄 Grazing vs Herbivore Species Richness
* 🌾 Mowing vs Herbivore Species Richness
* 🌱 Plant Species Richness vs Herbivore Species Richness
* 🔥 Correlation Heatmap
* 📈 Feature Importance Plot
* 🎯 Actual vs Predicted Values

---

# 🔑 Key Findings

* Higher fertilization intensity showed a weak negative relationship with herbivore species richness.
* Grazing intensity exhibited little influence on herbivore diversity.
* Mowing intensity demonstrated a slight negative association with herbivore richness.
* Plant species richness showed a stronger ecological relationship with herbivore diversity than grassland management practices alone.
* The Random Forest model identified the most influential predictors but achieved limited predictive accuracy, emphasizing the multifactorial nature of biodiversity.

---

# 📁 Repository Structure

```
Grassland-Management-and-Arthropod-Biodiversity/
│
├── Grassland_Management_and_Insect_Biodiversity.ipynb
├── data/
│   └── 04_SEMData_2009.xlsx
├── images/
│   ├── fertilization_vs_herbivores.png
│   ├── grazing_vs_herbivores.png
│   ├── mowing_vs_herbivores.png
│   ├── plant_vs_herbivores.png
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   └── actual_vs_predicted.png
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 🚀 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Scientific Data Visualization
* Correlation Analysis
* Ecological Data Interpretation
* Machine Learning with Random Forest
* Feature Importance Analysis
* Scientific Reporting

---

# 📚 Future Improvements

* Incorporate climatic variables (temperature and rainfall).
* Compare multiple machine learning algorithms.
* Perform statistical significance testing.
* Expand the dataset with additional ecological predictors.
* Develop an interactive dashboard using Plotly or Streamlit.

---

# 👩‍🔬 Author

**Maham Taqi**

Bachelor of Science in Molecular Biology

*Passionate about biodiversity, bioinformatics, ecological data science, and applying Python to solve biological research questions.*

---
