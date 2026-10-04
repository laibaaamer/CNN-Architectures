# 🖼️ CIFAR-10 Image Classification using CNN

A deep learning project that implements a **Convolutional Neural Network (CNN)** using **PyTorch** for image classification on the **CIFAR-10 dataset**.

The model is trained to classify images into 10 different categories and evaluated using test-set performance.

---

## 🎯 Project Objective

The goal of this project is to build and train a CNN from scratch using PyTorch and understand the complete image-classification workflow.

The project covers:

* Loading the CIFAR-10 dataset
* Image preprocessing
* CNN architecture design
* Model training
* Loss optimization
* Model evaluation
* Classification accuracy analysis

---

## 📊 Dataset

The project uses the **CIFAR-10 dataset**, which contains:

* **50,000** training images
* **10,000** test images
* **10 classes**
* RGB images of size **32 × 32 pixels**

### Classes

```text
airplane
automobile
bird
cat
deer
dog
frog
horse
ship
truck
```

---

## 🧠 CNN Architecture

The model uses convolutional layers to extract visual features from the input images.

The general architecture consists of:

```text
Input Image
     ↓
Convolutional Layer
     ↓
Activation Function
     ↓
Pooling
     ↓
Convolutional Layer
     ↓
Activation Function
     ↓
Pooling
     ↓
Flatten
     ↓
Fully Connected Layer
     ↓
Output Layer
     ↓
10 Classes
```

CNNs are particularly useful for image classification because convolutional layers can learn spatial features such as edges, shapes, and textures.

---

## 🛠️ Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib
* CIFAR-10 Dataset

---

## 📁 Project Structure

```text
cifar10-cnn-pytorch/
│
├── cifar10_cnn.py
├── requirements.txt
├── README.md
└── .gitignore
```

### File Description

| File                | Description                             |
| ------------------- | --------------------------------------- |
| `cifar10_cnn.py`    | Main PyTorch CNN implementation         |
| `requirements.txt`  | Required Python libraries               |
| `README.md`         | Project documentation                   |
| `.gitignore`        | Files excluded from Git                 |

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/cifar10-cnn-pytorch.git
```

Then:

```bash
cd cifar10-cnn-pytorch
```

---

### 2. Create a Virtual Environment

Using Conda:

```bash
conda create -n cifar10-cnn python=3.11
```

Activate it:

```bash
conda activate cifar10-cnn
```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

To run the Python script:

```bash
python cifar10_cnn.py
```

and run the cells sequentially.

---

## 🔄 Training Workflow

The project follows this workflow:

```text
CIFAR-10 Dataset
       ↓
Data Loading
       ↓
Image Transformation
       ↓
Train/Test Split
       ↓
CNN Model
       ↓
Forward Pass
       ↓
Loss Calculation
       ↓
Backpropagation
       ↓
Optimizer Update
       ↓
Model Evaluation
       ↓
Test Accuracy
```

---

## 📈 Model Training

During training, the model learns image features through multiple forward and backward passes.

The training process includes:

1. Load a batch of images.
2. Perform a forward pass.
3. Calculate classification loss.
4. Perform backpropagation.
5. Update model parameters using the optimizer.
6. Repeat for multiple epochs.
7. Evaluate the trained model on the test dataset.

---

## 🧪 Evaluation

The trained CNN is evaluated using the CIFAR-10 test set.

The primary evaluation metric is:

**Classification Accuracy**

```text
Accuracy = Correct Predictions / Total Predictions
```

The project can also be extended to include:

* Confusion matrix
* Per-class accuracy
* Precision
* Recall
* F1-score

---

## 📌 Results

Add your actual training results here after running the final version of the model.

Example:

```text
Test Accuracy: 72.47%
```


## 💡 Key Learning Outcomes

This project provided practical experience with:

* Convolutional Neural Networks
* PyTorch
* Torchvision
* Image classification
* Dataset preprocessing
* Training and validation workflows
* Loss functions
* Optimizers
* Backpropagation
* Model evaluation

---

## 🚀 Future Improvements

Possible improvements include:

* Data augmentation
* Batch normalization
* Dropout
* Learning-rate scheduling
* Transfer learning
* ResNet-based architecture
* Hyperparameter tuning
* Confusion matrix visualization
* Per-class performance analysis

---

## 👩‍💻 Author

**Laiba Aamer**

BS Artificial Intelligence Student

Interested in:

* Artificial Intelligence
* Machine Learning
* Deep Learning
* Computer Vision
* Generative AI

---

## 📄 License

This project is created for educational and portfolio purposes.
