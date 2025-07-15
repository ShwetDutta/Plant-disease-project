# 🌿 Plant Leaf Disease Detection System using AI Algorithms

This project uses **Convolutional Neural Networks (CNN)** to classify plant leaf images into various disease categories or healthy leaves. It was built using the **PlantVillage dataset** and **TensorFlow/Keras**.

---

## 📁 Folder Structure

📂 Project Root
├── 📂 Notebooks/ # Jupyter notebook(s)
│ └── Plant_Leaf_Disease_Classifier.ipynb
├── 📂 saved_models/ # Trained model files (optional)
│ └── plant_disease_model.h5 (excluded from GitHub)
├── 📄 requirements.txt # Python dependencies
├── 📄 .gitignore # Git ignore config


---

## 📦 Dataset

This project uses the [PlantVillage dataset](https://www.kaggle.com/datasets/emmarex/plantdisease).  
Due to its large size, the dataset is **not included in this repository**.

### 📥 How to Use:
1. Download the dataset from Kaggle.
2. Extract it.
3. Place it inside the root folder as:

Project_Root/
└── PlantVillage/
└── Tomato___Target_Spot/
└── Potato___Early_blight/
└── ...


---

## 🧠 Model Overview

- **Architecture**: CNN (Convolutional Neural Network)  
- **Input Size**: 180x180 RGB Images  
- **Output**: 13 Classes (12 diseases + 1 healthy)  
- **Loss Function**: Sparse Categorical Crossentropy  
- **Optimizer**: Adam  
- **Metrics**: Accuracy  

---

## 🛠️ Setup & Installation

### 1. Clone this repository
       ```
          git clone https://github.com/ShwetDutta/plant-disease-project.git
          cd plant-disease-project

### 2. Create a virtual environment (optional but recommended)
       ```bash
         python -m venv venv
         
         # On Windows:
         venv\Scripts\activate
         
         # On Mac/Linux:
         source venv/bin/activate

### 3. Install dependencies
      ```bash
         pip install -r requirements.txt

### 4. Ensure the dataset is placed in:
      ```bash
        PlantVillage/

#🚀 How to Run
▶️ Run the notebook

      ```bash
      jupyter notebook

Open Plant_Leaf_Disease_Classifier.ipynb.

Run all cells to:

Load and preprocess the dataset

Train the model

Save the model

Predict on a custom test image

🖼️ Sample Output:

      ```vbnet
      Predicted Class: Tomato___Target_Spot (99.40% confidence)


Result:

| Metric              | Value                                     |
| ------------------- | ----------------------------------------- |
| Training Accuracy   | \~97%                                     |
| Validation Accuracy | \~88%                                     |
| Total Images        | \~18,000                                  |
| Saved Models        | `plant_disease_model.h5`, `best_model.h5` |

🔗 Resources
📂 Dataset (Kaggle): PlantVillage on Kaggle

💾 Trained Model (Google Drive): [Download Model (.h5)](https://drive.google.com/drive/folders/1VI0NVFQTYwYp_8dqnm_0B9qAbC9Gsi_e?usp=drive_link)

💡 Future Improvements
Add a web interface using Flask or Streamlit

Integrate Grad-CAM for visual explainability

Convert model to TensorFlow Lite for mobile deployment

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss.

📜 License
This project was developed as part of an AI/ML internship submission and is intended for educational use.

🙋‍♂️ Acknowledgments
📊 Dataset: PlantVillage via Kaggle

🔧 Tools: TensorFlow/Keras













