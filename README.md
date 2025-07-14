# 🌿 Plant Leaf Disease Detection System using AI Algorithms

This project uses Convolutional Neural Networks (CNN) to classify plant leaf images into various disease categories or healthy leaves. It was built using the **PlantVillage dataset** and TensorFlow/Keras.

---

## 📁 Folder Structure

📂 Project Root
├── 📂 PlantVillage/ # Dataset folder
├── 📂 Notebooks/ # Jupyter notebook(s)
│ └── 01_dataset_preprocessing.ipynb
├── 📂 Saved Models/ # Trained models (.h5 files)
│ ├── best_model.h5
│ └── plant_disease_model.h5
├── 📄 requirements.txt # Python dependencies


---

## 🧠 Model Overview

- **Model**: CNN (Convolutional Neural Network)
- **Input Size**: 180x180 RGB Images
- **Output**: 13 Classes (12 diseases + 1 healthy)
- **Loss Function**: Sparse Categorical Crossentropy
- **Optimizer**: Adam
- **Metrics**: Accuracy

---

## 🛠️ Setup & Installation

1. **Clone this repository**
```bash
git clone https://github.com/yourusername/plant-leaf-disease-detection.git
cd plant-leaf-disease-detection

2. **Create a virtual environment (optional but recommended)**
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On Mac/Linux:
source venv/bin/activate

3. **Install dependencies**
```bash
pip install -r requirements.txt

4.Ensure the dataset is placed in the PlantVillage/ folder

🚀 How to Run
Open the Jupyter Notebook

bash
Copy
Edit
jupyter notebook
Open and run all cells in 01_dataset_preprocessing.ipynb.

Test with a custom image
Use the final cells of the notebook to load the saved model and test predictions.

🖼️ Sample Output
vbnet
Copy
Edit
Predicted Class: Tomato___Target_Spot (99.40% confidence)
📊 Results
Training Accuracy: ~97%

Validation Accuracy: ~88%

Model saved as: plant_disease_model.h5, best_model.h5

🧪 Dataset
Source: PlantVillage Dataset

Classes: 13

Images: ~18,000

📌 Future Improvements
Add a web interface using Flask or Streamlit

Integrate Grad-CAM for interpretability

Convert model for mobile use (TensorFlow Lite)

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first.

📜 License
This project is part of an online internship submission and is for educational purposes only.

🙋‍♂️ Acknowledgments
Dataset by PlantVillage via Kaggle

TensorFlow/Keras for model development
