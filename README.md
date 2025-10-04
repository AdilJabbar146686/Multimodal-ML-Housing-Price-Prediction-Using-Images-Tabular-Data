# House Price Prediction (Task 3)

This project predicts house prices using machine learning. It includes data preprocessing, model training, evaluation, and saving a trained model (`best_model.h5`).

---

### Structure
task3/
├── houses_dataset/ # Dataset folder
├── best_model.h5 # Saved trained model
└── task3.ipynb # Main Jupyter Notebook

yaml
Copy code

---

### Tools & Libraries
Python • Jupyter Notebook • TensorFlow/Keras • Pandas • NumPy • Matplotlib • Scikit-learn

---

### Run Instructions
```bash
git [clone https://github.com/<your-username>/task3.git](https://github.com/AdilJabbar146686/Multimodal-ML-Housing-Price-Prediction-Using-Images-Tabular-Data.git)
cd Multimodal ML – Housing Price Prediction Using Images + Tabular
Data
pip install -r requirements.txt
jupyter notebook task3.ipynb
# Load Saved Model
python
Copy code
from tensorflow.keras.models import load_model
model = load_model('best_model.h5')
# Highlights
Data preprocessing & feature engineering

Model training & evaluation

Visualization of actual vs predicted prices

Saved best model for reuse

# Author
Adil Jabbar
# email
adiljabbar146686@gmail.com

License
MIT License — free to use and modify.
