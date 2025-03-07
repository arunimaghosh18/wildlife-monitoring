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

---

### 2️⃣ Preprocessing
Run the preprocessing script to prepare the dataset:
```bash
python wildlife_monitoring.py
```

---

###3️⃣ Run K-Means Clustering
Choose the appropriate clustering method:

Grouped Clusters:
```bash
python kmeans.py
```

Individual Species Clustering:
```bash
python kmeans_specieswise.py
```

---

###4️⃣ Run Decision Tree Model
Run the Decision Tree script for habitat suitability prediction:
```bash
python tree.py
```

---

###5️⃣ Visualization
Use Tableau for visualization:

First Visualization: 📌 Plots all species on a map based on clusters. Filters can be applied by cluster number and species name.
Second Visualization: 📌 Plots suitable habitat (coordinates) for each species based on maximum count.


---

###Notes
Ensure Tableau is installed to visualize the processed data.
Use the generated CSV files to create maps for better insights into species distribution and conservation strategies.

