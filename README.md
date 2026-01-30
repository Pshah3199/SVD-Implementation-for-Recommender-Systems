# SVD-Implementation-for-Recommender-Systems

This repository contains a practical implementation of Singular Value Decomposition (SVD) 
for recommender systems using the mirror data to MovieLens dataset, focusing on sparse user–item rating matrices.

Files
	•	01_Manual_SVD_Implementation.ipynb
Manual, step-wise SVD for understanding the mathematics and flow.
	•	02_NumPy_SVD_Implementation.ipynb
Clean NumPy built-in SVD on a fixed example matrix.
Outputs only reconstructed matrix and RMSE.
	•	03_ScikitLearn_Truncated_SVD_Implementation.ipynb
Truncated SVD on a fixed example using scikit-learn for low-rank approximation.

⸻

📊 Dataset
	•	MovieLens 100K (Mirror sample used for visualization)
	•	Sparse user–item rating matrix

⸻

📈 Evaluation
	•	RMSE computed on known ratings to measure reconstruction error.

⸻

🧠 Key Idea
	•	Full SVD → exact reconstruction
	•	Truncated SVD → latent factors + better generalization

⸻

🎯 Use Case
	•	Academic posters
	•	Learning recommender systems
	•	SVD intuition and practice
