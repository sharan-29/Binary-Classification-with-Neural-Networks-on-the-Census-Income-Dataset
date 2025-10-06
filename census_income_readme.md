# Census Income Prediction (PyTorch)

This project builds a binary classification model using **PyTorch** to predict whether an individual earns more than $50,000 annually based on demographic data from the Census Income dataset.

---

## 📊 Dataset
The dataset contains demographic information such as:
- Age  
- Sex  
- Education level  
- Marital status  
- Work class  
- Occupation  
- Hours per week  
- Income label (`<=50K` or `>50K`)

You can download the dataset here:  
[UCI Census Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult)

---

## ⚙️ Setup Instructions

### 1️⃣ Clone this repository
```bash
git clone https://github.com/yourusername/census-income-prediction.git
cd census-income-prediction
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the model
```bash
python main.py
```

---

## 🤠 Model Details

- **Framework:** PyTorch  
- **Model Type:** Feedforward Neural Network  
- **Loss Function:** Binary Cross-Entropy  
- **Optimizer:** Adam  
- **Evaluation Metric:** Accuracy  

---

## 🔮 Predict New Input

You can input new user details (like age, education, hours per week) and the model will predict whether their income is likely `<=50K` or `>50K`.

### 📊 Example Output
```
Epoch 200 | Train Loss: 0.3089 | Val Loss: 0.3108 | Val Acc: 0.84
Predicted Income: >50K
```

---

## 👩‍💻 Author

Sharan Kumar G  
AIDS Students

---

### ✅ Summary of Project Files
| File | Purpose |
|------|----------|
| `requirements.txt` | Lists dependencies |
| `README.md` | Explains the project setup, usage, and details |
| `income.csv` | Dataset |
| `main.py` | Model training and prediction code |

