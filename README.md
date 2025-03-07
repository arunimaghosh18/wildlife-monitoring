# Wildlife and Habitat Monitoring

This project leverages **big data and machine learning** to analyze species distribution and assess habitat suitability, contributing to **Sustainable Development Goal 15 (SDG 15: Life on Land)**. Using **Apache Spark and PySpark MLlib**, the project processes large-scale biodiversity data from the **Global Biodiversity Information Facility (GBIF)**. **K-means clustering** is applied to group species based on geographic proximity, while a **Decision Tree model** predicts habitat suitability. The results are visualized using **Tableau**, providing actionable insights for conservation efforts.

---

## Features
✅ **Big Data Processing**: Utilizes Apache Spark to handle large biodiversity datasets efficiently.  
✅ **Species Clustering**: Uses K-means clustering to identify biodiversity hotspots.  
✅ **Habitat Suitability Prediction**: Implements a Decision Tree classifier to assess suitable habitats for species.  
✅ **Data Visualization**: Employs Tableau to create interactive maps and graphs for conservation analysis.  

---

## Technologies Used
- **Apache Spark** (Big Data Processing)
- **PySpark MLlib** (Machine Learning)
- **Tableau** (Data Visualization)
- **GBIF Dataset** (Biodiversity Data)

---

## Setup and Execution

### 1️⃣ Install Dependencies
Ensure you have the necessary dependencies installed:
```bash
pip install pyspark
```
### 2️⃣ Preprocessing
Run the preprocessing script to prepare the dataset:
```bash
python wildlife_monitoring.py
```
Output generated at:
```bash
dataset/output.csv/part-00000-f8f7d0bc-a5bc-40e3-a806-dc5dfb385e15-c000.csv
```


