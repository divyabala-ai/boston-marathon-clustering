# Boston Marathon Clustering

## Overview
This project uses Boston Marathon runner data to identify meaningful groups based on demographics and performance.  
The workflow includes K-Means and Gaussian Mixture Model (GMM) clustering, dimensionality reduction with PCA and t-SNE, and analysis of gender, age, and finish time distributions within clusters.

## Project Workflow
1. **Data Exploration**  
   - Loaded Boston Marathon dataset for a post-2012 year with complete demographic and performance information.  
   - Checked for missing values, cleaned data, and standardized numeric features.

2. **K-Means Clustering**  
   - Applied PCA for dimensionality reduction and visualized clusters for K = 2–10.  
   - Calculated silhouette scores to assess optimal K.  
   - Created gender-based bar graphs per cluster.  
   - Analyzed age group distribution (18–25, 26–40, 41–70) across clusters.  
   - Compared finish times between clusters.

3. **Gaussian Mixture Model (GMM)**  
   - Applied PCA for visualization with GMM clusters for K = 2–10.  
   - Computed silhouette scores and selected optimal K.  
   - Repeated gender, age group, and finish time analyses.

4. **t-SNE Visualization**  
   - Reduced dimensions with t-SNE for both K-Means and GMM results.  
   - Visualized clusters in 2D space for better separation insight.

5. **Findings**  
   - Certain clusters were dominated by younger runners with faster finish times.  
   - Gender distribution varied significantly between clusters.  
   - GMM sometimes provided better separation than K-Means for certain K values.  
   - PCA + K-Means offered more interpretable results, while t-SNE gave better visual separation.

## Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

## Dataset
Boston Marathon dataset (post-2012), containing runner demographics and performance statistics.
