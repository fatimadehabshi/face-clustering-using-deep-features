# Image Clustering with Deep Feature Extraction

This project implements a complete clustering pipeline for grouping face images of 15 individuals.  
The goal is to extract meaningful visual features using pre-trained CNNs, reduce feature dimensionality, and apply multiple clustering algorithms to evaluate their effectiveness.

---

## Project Overview
The project consists of four main phases (based on the assignment specification):  
- **Feature Extraction:** Using pre-trained VGG16 and ResNet50 networks to generate feature vectors for each image.  
- **Dimensionality Reduction:** Applying PCA and t-SNE to project high-dimensional embeddings into lower dimensions for clustering and visualization.  
- **Clustering Algorithms:** Implementing and comparing K-Means, DBSCAN, Mean Shift, and Agglomerative clustering.  
- **Evaluation:** Analyzing clustering performance visually and using metrics such as the Rand Index.  

(Descriptions of these phases appear in the assignment document, pages 1–10  :contentReference[oaicite:1]{index=1})

---

## Methods Used

### **1. Feature Extraction**
Pre-trained deep learning models:
- **VGG16**
- **ResNet50**

These models generate high-dimensional feature vectors representing each image.

### **2. Dimensionality Reduction**
- **PCA** for global structure preservation  
- **t-SNE** for local neighborhood preservation  

### **3. Clustering Algorithms**
Implemented and compared:
- **K-Means**  
- **DBSCAN**  
- **Mean Shift**  
- **Agglomerative Clustering**

### **4. Evaluation**
- Visual cluster plots (ResNet50 & VGG16 features)  
- Rand Index to compare predicted clusters with true labels  
  (discussed in Phase 6 of the report  :contentReference[oaicite:2]{index=2})
