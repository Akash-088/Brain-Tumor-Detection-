# 🧠 Brain Tumor Detection using Deep Learning

This project implements a Convolutional Neural Network (CNN) to detect and classify brain tumors from MRI scans into four categories:

- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **No Tumor**

The model is developed using the PyTorch deep learning framework and executed in a Google Colab environment.

---

## 📁 Dataset Structure

The dataset is organized into two main directories:
data/
├── Training/
│ ├── glioma/
│ ├── meningioma/
│ ├── notumor/
│ └── pituitary/
└── Testing/
├── glioma/
├── meningioma/
├── notumor/
└── pituitary/

*Note: Ensure that the dataset is properly uploaded to your Google Drive and the paths in the code are correctly set.*

---

## 🛠️ Features

- **Data Preprocessing**: Normalization and resizing of images to ensure uniformity.
- **Model Architecture**: A CNN model with multiple convolutional and pooling layers, followed by fully connected layers.
- **Training**: Implemented with appropriate loss functions and optimizers.
- **Evaluation**: Accuracy and loss metrics are calculated on the test dataset.
- **Visualization**: Loss and accuracy curves plotted for analysis.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Google Colab account
- Google Drive with the dataset uploaded

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Akash-088/Brain-Tumor-Detection-.git
2.  Upload the dataset to Google Drive:
    Place the data folder in your Google Drive.

3. Open the notebook:
   Open Brain_Tumor_Detection.ipynb in Google Colab.

4. Mount Google Drive:
   In the Colab notebook, run:

   from google.colab import drive
   drive.mount('/content/drive')

5. Set the dataset path:
   Ensure the path to the dataset in the notebook matches the location in your Google Drive.

6. Run the notebook:
   Execute the cells sequentially to train and evaluate the model.

---

## 📊 Results

After training, the model achieved the following performance metrics:

- **Training Accuracy:** 100%
- **Validation Accuracy:** 93.8%
- **Test Accuracy:** 95.4%
  
---

📈 Visualizations





