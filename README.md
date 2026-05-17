# Neural Network Fundamentals and Training Behavior Analysis

## Objective
The objective of this project is to build and analyze a feed-forward neural network model for customer churn prediction using a structured dataset. The project demonstrates neural network training, forward propagation, backpropagation, loss calculation, and hyperparameter experimentation.

---

## Dataset
The dataset contains customer-related features such as:
- Region
- Plan type
- Contract type
- Monthly charges
- Data usage
- Satisfaction score
- Payment delays
- Referral count
- Churn status

Target variable:
- `churn`  
  - 0 → Non-churn customer
  - 1 → Churn customer

---

## Tasks Performed

### 1. Dataset Understanding
- Dataset exploration
- Missing value check
- Statistical summary
- Target variable distribution analysis

### 2. Data Preprocessing
- Removed identifier column
- Encoded categorical variables
- Feature scaling using StandardScaler
- Train-test splitting

### 3. Neural Network Model Building
- Built feed-forward neural network using TensorFlow/Keras
- Used Dense hidden layers
- ReLU and ELU activation functions
- Sigmoid output activation for binary classification

### 4. Model Training and Evaluation
- Trained neural network model
- Evaluated using:
  - Accuracy
  - Loss
  - Confusion matrix
  - Classification report

### 5. Hyperparameter Experimentation
Experiments were performed by changing:
- Number of hidden layers
- Number of neurons
- Activation functions
- Learning rate
- Number of epochs

### 6. Final Reflection
Discussed:
- Role of weights and biases
- Importance of activation functions
- Effect of learning rate
- Underfitting and overfitting analysis

---

## Experiment Summary

 Experiment  Description 
---|--|
 Exp 1  Baseline model 
 Exp 2  Two hidden layers 
 Exp 3  ELU activation with more neurons 
 Exp 4  Higher learning rate 
 Exp 5  Increased epochs 

---

## Results
The model achieved high overall accuracy; however, confusion matrix and classification report analysis showed challenges in predicting minority churn cases due to dataset imbalance.

---

## Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow

---

## Project Structure

```text
part-1-neural-network-analysis/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
└── results/
    ├── model_comparison_table.csv
    └── evaluation_outputs.png
```
