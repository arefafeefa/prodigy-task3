🐶🐱 Cat vs Dog Image Classification using SVM
📘 Project Overview

This project implements a Support Vector Machine (SVM) model to classify images of cats and dogs using the Kaggle Cats vs Dogs dataset.
Each image is preprocessed by resizing to a fixed size (64×64), flattened into a 1D vector, and used as input to train the SVM classifier.
The model is then evaluated on unseen validation data and tested on random images from the test folder for visual predictions.

🧰 Technologies Used

Python 🐍

OpenCV – Image reading and resizing

NumPy – Data manipulation

Scikit-learn – SVM model, accuracy evaluation, train/test split

Matplotlib – Visualization of predictions

Joblib – Saving and loading the trained model

📊 Dataset

Source: Kaggle Dogs vs Cats Dataset

Train Folder: 100 labeled images (cat and dog)

Test1 Folder: 100 unlabeled images

Used Sample: 100 images (for faster model training)

All images are resized to 64×64 before training.

📈 Visualizations

Displays model accuracy on unseen validation images.

Shows a 3×3 grid of random test images from the test1 folder with predicted labels (Cat or Dog).

🗂️ File Structure
📁 Cat-Dog-SVM-Classifier
│

├── Images
   
    ├── train/                   # Training images (cats & dogs)
    ├── test1/                   # Test images (unlabeled)

├── svm_cat_dog_model.pkl    # Saved SVM model

├── Task3.py           # Main Python script

└── README.md                # Project overview and setup
