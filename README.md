# Multivariate Statistical Analysis of Geomyoid Rodent Morphology

[cite_start]**Author:** Vigneshwar Lokoji [cite: 1]

## 📌 Project Overview
[cite_start]The primary objective of this study was to analyze the morphological structure of Geomyoid rodent skulls using multivariate statistics[cite: 4]. [cite_start]The goal was to determine if cranial measurements provide a sufficient biological signal to distinguish between different taxa, specifically looking at differences between families, genera, and species[cite: 5].

## 📂 Dataset
[cite_start]The analysis utilizes a dataset containing **181 observations** covering **39 different species**.
* [cite_start]**Source File:** `DASC5323Proj (1).csv` 
* [cite_start]**Quantitative Variables:** 15 skull measurements (e.g., width, length, depth)[cite: 9].
* [cite_start]**Categorical/Grouping Variables:** Sex, Species, and Genus[cite: 10, 18].
* [cite_start]**Data Preparation:** The data was cleaned to ensure no missing values, and a new column for "Genus" was created to facilitate broader taxonomic grouping[cite: 11, 12].


## ⚙️ Methodology
[cite_start]Five specific statistical methods were utilized to analyze the data and identify patterns[cite: 120]:

1.  [cite_start]**Exploratory Data Analysis (EDA):** Included correlation heatmaps, boxplots, and scatter matrices to visualize multicollinearity and initial group differences[cite: 104, 110, 113].
2.  [cite_start]**MANOVA (Multivariate Analysis of Variance):** Used as a "sanity check" to test if the groups were statistically different[cite: 121].
3.  [cite_start]**Factor Analysis:** Employed to reduce the 15 correlated variables into latent factors explaining the variation in skull shape[cite: 129, 130].
4.  [cite_start]**Hierarchical Clustering:** Used to generate dendrograms to see if specimens grouped naturally without prior labeling[cite: 172].
5.  [cite_start]**Multidimensional Scaling (MDS):** Visualized the complex 15-dimensional data on a flat 2D plot to observe genera separation[cite: 175, 176].
6.  [cite_start]**Linear Discriminant Analysis (LDA):** Identified axes that maximize class separation to define the boundaries between rodent taxa[cite: 180].

## 📊 Key Findings
[cite_start]The study concluded that quantitative skull measurements are highly effective for taxonomic classification in Geomyoid rodents[cite: 204].

* [cite_start]**Statistical Significance:** The MANOVA results were significant ($p < 2.2e^{-16}$), confirming real biological differences in skull morphology[cite: 122].
* [cite_start]**Dimensionality:** Factor Analysis revealed that 3 underlying factors (Width, Length, and Shape) could explain the data structure[cite: 193, 202].
* **Class Separation:** LDA proved to be the most powerful tool. [cite_start]The first discriminant function (LD1) accounted for **83.3%** of the between-group variance[cite: 198, 199].
* [cite_start]**Clustering:** Visualizations confirmed that while there is some overlap between closely related species, broader Genera (such as *Cratogeomys* vs. *Geomys*) occupy distinct regions of the morphological space[cite: 197].

## 🛠️ Technologies Used
* [cite_start]**Language:** R [cite: 14]
* **Key Techniques:** Multivariate Statistics, Dimensionality Reduction, Clustering.

## 📈 Visualizations
The project generates several key plots to visualize the data:
* Correlation Heatmaps
* Boxplots of Cranial Measurements (e.g., GCL)
* Dendrograms for Hierarchical Clustering
* MDS 2D Projection Plots
* LDA Canonical Plots

---
[cite_start]*This project serves as a foundation for assessing how well-defined the boundaries are between different rodent taxa based on cranial morphology.* [cite: 183]
