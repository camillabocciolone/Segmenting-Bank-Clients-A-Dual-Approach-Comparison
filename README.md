# Segmenting Bank Clients – Dual Approach

This project focuses on **customer segmentation in banking** using data-driven unsupervised learning techniques.  
The objective is to identify meaningful financial personas that support targeted marketing, personalized services and better strategic decision-making.

The analysis follows **two complementary segmentation approaches**, providing both a statistically robust framework and an operationally scalable solution.

---

## 📂 Project Structure

- **SegmentingClientsPoliMI_ExtendedAbstract_group6.pdf : Abstract**  
  Short scientific report describing the problem, methodology and main results of the segmentation analysis.

- **Presentation (PPT)**  
  Slide deck summarizing the project motivation, data preparation, clustering methods, validation results and identified customer personas.

- **SegmentingClientsPoliMI_1_group6.ipynb : Notebook 1 (NB1)**  
  Main segmentation pipeline based on **mixed-type data clustering**.  
  Includes:
  - weighted Gower distance  
  - dimensionality reduction (PCA, t-SNE, UMAP, PaCMAP)  
  - multiple clustering algorithms comparison  
  - internal validation metrics  
  - bootstrap stability analysis  
  - financial persona profiling  

- **SegmentingClientsPoliMI_2_group6.ipynb : Notebook 2 (NB2)**  
  Alternative segmentation based on **K-Means clustering** applied to numerical features.  
  Focuses on:
  - model selection via validation metrics and elbow analysis  
  - fine-grained customer personas  
  - scalable deployment through centroid-based assignment  

---

## 🎯 Goal

Provide a **robust and interpretable segmentation of bank clients**, balancing methodological rigor with practical usability for real-world financial decision processes.
