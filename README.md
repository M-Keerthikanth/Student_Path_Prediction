Student Path Prediction using Artificial Neural Network (ANN)

Project Title:
**Student Career Path Prediction using ANN**

Problem Statement:

Students often face confusion in choosing the right career path due to lack of proper guidance. This project aims to solve this problem by using an **Artificial Neural Network (ANN)** to predict suitable career options based on student performance and skills.

Objectives:

* To develop a predictive system using ANN
* To analyze student academic and skill data
* To recommend the most suitable career path
* To provide structured guidance for future planning

Methodology:

The system follows these steps:

1. Data Collection

  Student dataset containing marks and skill attributes

2. Data Preprocessing

   * Feature selection
   * Label encoding of career output

3. Model Building

   * Artificial Neural Network using Keras

4. Training

   * Model trained on dataset

5. Testing & Prediction

   * Predicts career path for new input

6. Output Display

   * Shows predicted career
   * Displays detailed career path guidance

Technologies Used:

* Python
* Pandas
* NumPy
* Scikit-learn
* TensorFlow / Keras
* Matplotlib

Dataset Description:

The dataset includes the following features:

* Math Marks
* Science Marks
* Coding Skills
* Communication Skills
* Career (Target)

Model Architecture:

* Input Layer: 4 neurons
* Hidden Layer 1: 10 neurons (ReLU)
* Hidden Layer 2: 8 neurons (ReLU)
* Output Layer: 1 neuron (Sigmoid)

How to Run:

1. Install required libraries:


pip install pandas numpy scikit-learn tensorflow matplotlib


2. Open the notebook:


Student_Path_Prediction.ipynb


3. Upload or create `career_Students.csv`

4. Run all cells


Output:

* Predicted Career (Engineer / Manager, etc.)
* Career Path Guidance (steps to achieve career)
* Accuracy and evaluation metrics

Features:

* Uses ANN for prediction
* Provides career guidance (not just prediction)
* Simple and easy to understand
* Can be extended to more careers

 Limitations:

* Small dataset
* Limited career options
* Accuracy depends on input data

Future Scope:

* Add more career categories
* Use real-world large datasets
* Develop GUI or web app
* Improve accuracy using deep learning


Conclusion:

This project demonstrates how ANN can be effectively used to assist students in selecting appropriate career paths. It not only predicts outcomes but also provides actionable guidance, making it a useful tool for educational support systems.

Created by:

* Mekala Keerthikanth
* AIML
* Alliance University


