🧬 Breast Cancer Detection using Machine Learning
This project implements a binary classification model to accurately detect the presence of breast cancer using the Breast Cancer Wisconsin Diagnostic Dataset from scikit-learn. It serves as a practical demonstration of applying machine learning techniques to medical diagnostics.

🧪 Dataset
The dataset used is the built-in load_breast_cancer() from sklearn.datasets, consisting of 569 instances with 30 numeric features computed from digitized images of a fine needle aspirate (FNA) of a breast mass. These features describe characteristics of the cell nuclei present in the image.

Classes: Malignant (1), Benign (0)

Features: Mean radius, texture, perimeter, area, smoothness, etc.

⚙️ How the Model Works
Data Loading & Preprocessing

Imported the dataset using sklearn.datasets.load_breast_cancer()

Converted the data to a pandas DataFrame for easier manipulation and visualization

Data Splitting

Split into training and test sets using train_test_split()

Model Building

Implemented a Logistic Regression classifier

Trained on the training set to learn patterns that differentiate between malignant and benign tumors

Model Evaluation

Evaluated model performance using accuracy score

Tested on the test data to verify generalization ability

Prediction System

Built a custom input prediction system to classify new data points

🛠️ Technologies Used
Python: Core programming language

NumPy & Pandas: Data manipulation and numerical computation

Matplotlib: Data visualization

scikit-learn:

Data loading (datasets.load_breast_cancer)

Model building (LogisticRegression)

Model evaluation (accuracy_score)

Data splitting (train_test_split)

📊 Output
The model achieves high accuracy (99.88 %) in detecting breast cancer.

Helps in early-stage detection by providing predictions based on tumor measurements.
