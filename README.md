This project demonstrates a simple machine learning pipeline to predict student placement outcomes based on features like CGPA and resume scores using the Perceptron algorithm.

📂 Dataset
The dataset (placement.csv) includes:

cgpa: Student's CGPA

resume_score: Score based on resume quality

placed: Binary label indicating placement status

🧠 Model
The model used is the Perceptron from sklearn.linear_model, a basic binary classifier suited for linearly separable data.

📊 Visualization
The dataset is visualized using Seaborn to understand feature relationships and class separability.

📈 Output
Scatter plots of CGPA vs Resume Score, color-coded by placement.

Decision boundary visualization.

📌 Dependencies
Python ≥ 3.6

numpy

pandas

matplotlib

seaborn

scikit-learn
