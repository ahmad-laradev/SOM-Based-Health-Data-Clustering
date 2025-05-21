#  Clustering Health Data using Self-Organizing Maps (SOM)

This small project explores how we can use a **Self-Organizing Map (SOM)** to find patterns in health data — without any labels during training. It helps us group similar data points, like separating patients from healthy individuals, just based on their features.

##  What This Project Does

- Loads health-related data from files
- Combines and scales the data
- Trains a SOM (a type of unsupervised neural network)
- Assigns a label (Healthy or Patient) to each SOM unit based on training data
- Predicts the category of new, unlabeled samples using the trained SOM

##  Files Included

- `control.txt` – data from healthy people
- `patient.txt` – data from patients
- `Khalil.txt` – new test samples to predict
- `trained-som.pkl` – the saved model, scaler, and label map
- `Khalil_ahmed.ipynb` – full code notebook
- `som_lab_report.tex` – LaTeX report for documentation

##  How to Use It

1. Run the notebook `Khalil_ahmed.ipynb`
2. It trains a 3x3 SOM on the health data
3. It saves the trained model
4. It predicts the labels of new samples from `Khalil.txt`

##  Example Output

Sample 1: Predicted = Patient
Sample 2: Predicted = Healthy
Sample 3: Predicted = Unknown (not matched)


##  Tools & Libraries

- Python
- NumPy
- scikit-learn
- Pickle
- Jupyter Notebook

##  Report

The full write-up (objectives, results, and ideas for improvement) is in the `som_lab_report.tex` file. You can compile it to PDF using Overleaf or any LaTeX editor.

##  What's Done

-  SOM model trains and predicts properly
-  Clear code with readable output
-  Data files and trained model included

##  Ideas to Improve

- Add nice SOM visualizations (like U-Matrix or heatmaps)
- Try bigger grid sizes for more complex patterns
- Compare results with other clustering methods like K-Means or PCA

---

Thanks for checking out the project!   
Feel free to explore, fork, or reuse this as a learning tool.

