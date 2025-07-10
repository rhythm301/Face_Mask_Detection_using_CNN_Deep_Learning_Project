# Face Mask Detection Using CNN

This project demonstrates a deep learning model using **Convolutional Neural Networks (CNNs)** to classify whether a person is wearing a mask or not. It uses the **Face Mask Detection dataset from Kaggle** and is implemented entirely in a Jupyter Notebook for ease of experimentation and learning.

---

## 📌 Project Highlights

- 📥 Automated dataset download via Kaggle API
- 📊 Data visualization and preprocessing
- 🧠 CNN model built using TensorFlow/Keras
- 🧪 Model evaluation using accuracy and loss metrics
- 💾 Final model saved as `.h5` for deployment or future use

---

## 📂 Dataset

- Source: [Kaggle - Face Mask Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)
- Two classes:
  - `with_mask`
  - `without_mask`

The dataset is downloaded directly using the Kaggle API within the notebook.

---

## 🔧 Installation & Setup

### Prerequisites
- Python 3.8+
- Kaggle API Key (`kaggle.json`)

### Required Libraries

Install the required packages using pip:

pip install tensorflow keras opencv-python matplotlib seaborn pandas numpy kaggle
🚀 How to Run
Download your kaggle.json key from Kaggle API settings.

Upload it to the notebook environment.

Run all cells in the notebook:
📓 Face Mask Detection Using CNN.ipynb

The notebook:

Downloads the dataset

Preprocesses the images

Builds a CNN model

Trains and evaluates the model

Saves the trained model to disk (mask_detector_model.h5)

📈 Model Performance
Metric	Value
Accuracy	~97%
Image Size	128x128
Input Format	RGB Image
Loss Function	Binary Crossentropy

Visualizations of training vs validation accuracy and loss are provided in the notebook.

📁 Files in this Repo
graphql
Copy
Edit
├── Face Mask Detection Using CNN.ipynb  # Main project notebook
├── kaggle.json                          # Your Kaggle API token (not included, upload separately)
├── mask_detector_model.h5              # Saved trained model (output)
└── README.md                           # Project documentation


Tools


