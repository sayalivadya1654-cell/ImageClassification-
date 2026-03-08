# 🩺 Early Detection of Anemia Using Support Vector Machine on Eye Conjunctiva Colour

## 📌 Project Overview

Early detection of anemia is important for preventing serious health complications. Traditional diagnosis usually requires laboratory blood tests, which may not always be easily accessible in remote or resource-limited areas.

This project presents a **machine learning–based image classification system** that predicts whether a person is **anemic or non-anemic** by analyzing the **color of the eye conjunctiva**.

The system uses **image preprocessing and a Support Vector Machine (SVM) model** to classify eye images and assist in early anemia screening.

This project demonstrates how **machine learning and computer vision techniques** can be used to develop **low-cost healthcare diagnostic tools**.

---

# 🛠 Tech Stack

## Machine Learning

* Support Vector Machine (SVM)
* Scikit-learn

## Programming Language

* Python

## Data Processing

* NumPy
* Pandas

## Visualization

* Matplotlib
* Seaborn

## Development Environment

* Jupyter Notebook

---

# 🚀 Getting Started

Follow these instructions to run the project locally.

---

# ⚙ Prerequisites

Ensure the following are installed on your system:

* Python 3.8 or higher
* pip (Python package manager)
* Jupyter Notebook

Check Python version:

```bash
python --version
```

---

# 📥 Installation

Clone the repository:

```bash
git clone https://github.com/sayalivadya1654-cell/ImageClassification-.git
```

Navigate to the project directory:

```bash
cd ImageClassification-
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

If requirements file is not available, install the libraries manually:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

---

# ⚙ Configuration

Ensure the dataset containing **eye conjunctiva images** is available for training and testing.

The notebook contains steps for:

* Image preprocessing
* Feature extraction
* Model training
* Prediction

All configurations are handled within the **Jupyter Notebook (`anaemiasvm.ipynb`)**.

---

# ▶ Running the Application

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the file:

```
anaemiasvm.ipynb
```

Run the notebook cells sequentially to:

1. Load the dataset
2. Preprocess the images
3. Train the Support Vector Machine model
4. Evaluate model performance
5. Generate predictions

---

# ✨ Features

* Image-based anemia detection
* Machine learning classification using SVM
* Image preprocessing and feature extraction
* Data visualization for analysis
* Simple and interpretable model
* Demonstrates healthcare AI application

---

# 📂 Project Structure

```
ImageClassification-
│
├── anaemiasvm.ipynb     # Main notebook containing model training and prediction
├── README.md            # Project documentation
├── .gitignore           # Ignored files configuration
│
└── dataset/             # Eye conjunctiva image dataset (if added)
```

---

# 🔬 Prediction Pipeline

The anemia detection workflow follows these steps:

1️⃣ **Image Input**

Eye conjunctiva images are collected as the dataset.

2️⃣ **Image Preprocessing**

Images are processed to extract meaningful color and intensity features.

3️⃣ **Feature Extraction**

Important features related to conjunctiva color are extracted for model training.

4️⃣ **Model Training**

A **Support Vector Machine (SVM)** classifier is trained to distinguish between:

* Anemic
* Non-anemic

5️⃣ **Prediction**

The trained model predicts whether a new eye image indicates **possible anemia**.

---

# 🤝 Contributing

Contributions are welcome.

To contribute:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-new-improvement
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to your branch

```bash
git push origin feature-new-improvement
```

5. Create a Pull Request.

---

# 📜 License

This project is licensed under the **MIT License**.

---

⭐ If you find this project helpful, consider **starring the repository**.
