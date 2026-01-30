
This project implements a K-Nearest Neighbors (KNN) classifier to recognize handwritten digits using the MNIST dataset. The model classifies digits from 0 to 9 based on pixel intensity values.

Source: Kaggle  
Link: https://www.kaggle.com/datasets/oddrationale/mnist-in-csv  

Files used:
- mnist_train.csv
- mnist_test.csv  

Each row contains:
- First column: Digit label (0–9)
- Remaining columns: Pixel values (28 × 28 image)

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

- Loaded MNIST CSV files
- Handled missing values by replacing NaN with 0
- Applied feature scaling using StandardScaler
- Trained KNN model with multiple K values (3, 5, 7, 9)
- Selected best K based on accuracy
- Evaluated model using accuracy score and confusion matrix
- Visualized accuracy vs K graph
- Displayed predicted digit images

- Optimal K value selected based on highest accuracy
- Model achieved high classification accuracy
- Confusion matrix used to analyze misclassifications

1. Download dataset from Kaggle
2. Upload mnist_train.csv and mnist_test.csv to Google Colab
3. Run the Python script
4. View accuracy, confusion matrix, and predictions

## Conclusion
This project demonstrates distance-based classification using KNN and highlights the importance of feature scaling and K-value tuning in machine learning models.
