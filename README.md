# Pneumonia detection from chest X-rays

Binary image classifier that distinguishes **NORMAL** vs **PNEUMONIA** chest X-rays using a small convolutional neural network (CNN) in TensorFlow/Keras. Training and evaluation live in a Jupyter notebook.

> **Disclaimer:** This project is for learning and experimentation only. It is not a medical device and must not be used for clinical diagnosis.

## What it does

1. Loads and visualizes sample X-ray images (OpenCV + Matplotlib).
2. Builds train / validation / test pipelines.
3. Trains a simple CNN.
4. Reports **precision**, **recall**, and **F1** on the test set, plus a confusion matrix heatmap.

## Requirements

See `requirements.txt` for Python packages: NumPy, Pandas, Matplotlib, Seaborn, OpenCV, TensorFlow, scikit-learn, Jupyter.

## License & attribution
- Dataset: see Kaggle dataset page for terms of use and citation requirements (Mooney, 2018).
