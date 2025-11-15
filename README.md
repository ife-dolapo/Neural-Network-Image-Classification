# Neural-Network-Image-Classification
Image classification using a feedforward neural network on Fashion MNIST

Project Overview
This project implements a feedforward neural network using TensorFlow/Keras to classify images from the Fashion MNIST dataset. It demonstrates the power of deep learning over traditional machine learning for image classification tasks.
---

 Dataset
- **Fashion MNIST**: 70,000 grayscale images (28×28) across 10 fashion categories.
- Automatically loaded via `tensorflow.keras.datasets`.
---

## Setup Instructions

### 🔧 Option 1: Run in Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/)
2. Upload and open `Assignment 12 - Neural Network and Deep Learning Basics.ipynb`
3. Run all cells sequentially

### 🔧 Option 2: Run Locally
#### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Neural-Network-Image-Classification.git
cd Neural-Network-Image-Classification
```
#### 2. Create a Virtual Environment (Optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
### 3.Install Dependencies
```bash
pip install -r requirements.txt
```
'If no requirements.txt is provided, install manually:'
```bash
pip install tensorflow matplotlib seaborn numpy pandas
```
### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```
Then open `Assignment 12 - Neural Network and Deep Learning Basics.ipynb` and run the cells.

Features
- Data loading and normalization
- Feedforward neural network with ReLU and Softmax
- Training with validation split
- Evaluation using accuracy, precision, recall, F1-score
- Confusion matrix and training curve visualizations
- Deployment discussion: scalability, latency, integration

---
Files
├── Assignment 12 - Neural Network and Deep Learning Basics.ipynb                  # Main notebook
├── Report of Neural Network Image Classification Using Fashion MNIST.pdf          # 2-page summary
├── README.md                                                                      # Project overview and setup

---
Author
Ifedolapo
Business Intelligence Analyst | Machine Learning & Analytics Enthusiast
Focused on building scalable, transparent analytics workflows that connect technical depth to business impact.
