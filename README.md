# CIFAR-10 CNN with BatchNormalization

This project implements a **Convolutional Neural Network (CNN)** for **CIFAR-10 image classification**.  
It includes **Batch Normalization** for faster and more stable training and allows prediction on **custom images**.

---

## CIFAR-10 Classes
- airplane
- automobile
- bird
- cat
- deer
- dog
- frog
- horse
- ship
- truck

---

## Requirements
- Python 3.x
- TensorFlow 2.x
- NumPy
- Pandas
- Matplotlib
- scikit-learn

You can also install dependencies using:

```bash
pip install tensorflow matplotlib numpy pandas scikit-learn
```
## How to Run in Google Colab

1. **Open the Notebook**
   - Go to your GitHub repository.
   - Click on `cifar10_cnn.ipynb`.
   - Click **Open in Colab** (top-right) to launch the notebook.

2. **(Optional) Upload a Custom Image**
   - If you want to predict your own image, upload it to Colab:

## Make sure to update the filename in the notebook:
  
3. Run All Cells
   - Click Runtime → Run all
   - or press the play button on each cell sequentially.
   - The notebook will:
      - Load the CIFAR-10 dataset
      - Build and train the CNN with BatchNormalization
      - Evaluate the model on test data
      - Predict the class of your custom image
