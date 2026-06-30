# 📈 CSV Data Prediction using RNN (LSTM)

A simple Deep Learning project built using TensorFlow and LSTM (Long Short-Term Memory) to predict future values from CSV time-series data.

## 🚀 Features

- Upload CSV file
- Data preprocessing using MinMaxScaler
- Sequence generation
- Train LSTM model
- Predict future values
- Reverse scaling to original values

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

---

## 📂 Project Structure

```
project/
│
├── harsh.csv
├── RNN.ipynb
├── README.md
```

---

## 📥 Install Libraries

```bash
pip install tensorflow
pip install numpy
pip install pandas
pip install matplotlib
pip install scikit-learn
```

---

## ▶ Run Project

Open:

```bash
RNN.ipynb
```

Upload CSV file:

```python
from google.colab import files
uploaded = files.upload()
```

Run all cells.

---

## 📊 Dataset Format

CSV should contain:

```csv
Index
100
110
120
130
140
150
```

Example:

Input:

```
100
110
120
```

Output:

```
130
```

---

## 🧠 Model Architecture

```text
Input
 ↓
LSTM (50 Units)
 ↓
Dense (1)
 ↓
Prediction
```

---

## 📈 Sample Output

```text
Prediction:
[[11589.417]]
```

---

## 🔮 Future Improvements

- Multi-step prediction
- Better visualization
- Hyperparameter tuning
- Real-time CSV upload

---

## 👨‍💻 Author

Harsh Vardhan

Built with TensorFlow + LSTM 🚀
