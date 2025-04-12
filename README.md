**🏥 Patient Segmentation for Preventive Healthcare**
Project Overview
This project focuses on segmenting patients using unsupervised learning techniques to support preventive care planning in healthcare systems. By clustering patients based on key health and billing features, we can help care providers personalize treatment strategies, optimize resource allocation, and reduce unnecessary interventions.

**📌 Objective**
Use clustering (KMeans) on patient-level health and demographic data to identify distinct segments that can benefit from tailored preventive care.

**Methodology**
Data Source: Healthcare Dataset (Kaggle - Prasad22)

Techniques Used:

Data preprocessing (cleaning, encoding, scaling)

Dimensionality reduction with PCA

Clustering via KMeans

Visual analysis: scatter plots, heatmaps

**📊 Key Insights**
Patients are grouped into distinct clusters with similar age, room usage, and billing patterns.

One cluster showed significantly higher billing, likely indicating higher-risk patients requiring chronic care monitoring.

Another segment had low cost and low usage, potentially suitable for virtual care pathways or educational interventions.

**💼 Business Impact**
Personalized Care Plans: Enables hospitals to assign patients to targeted programs (e.g., chronic care, low-risk wellness).

Cost Optimization: Helps reduce unnecessary inpatient services for low-risk segments.

Operational Efficiency: Improves load balancing across departments by anticipating patient needs.

Strategic Planning: Supports policy decisions on staffing, service lines, and bundled care initiatives.

**Folder Structure**
data/: Source CSV

notebooks/: Exploratory & clustering workflow

visuals/: PCA plots, heatmaps for cluster analysis

**Tools Used**
Python (Pandas, Scikit-learn, Seaborn, Matplotlib)

Unsupervised learning (KMeans)

PCA for visualization

