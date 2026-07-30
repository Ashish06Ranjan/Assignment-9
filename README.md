# Assignment - 9 : Image Classification using Convolutional Neural Network (CNN)

## Assignment Information

- **Course:** Artificial Intelligence and Machine Learning
- **Assignment:** Assignment 9
- **Topic:** Image Classification using CNN
- **Dataset:** Cats vs Dogs Dataset

---

## Objective

The objective of this project is to build a Convolutional Neural Network (CNN) that can classify images as either a cat or a dog. The project demonstrates the complete image classification workflow, including data understanding, preprocessing, model development, training, evaluation, and performance analysis.

---

## Dataset

**Dataset Name:** Cats vs Dogs Dataset

**Dataset Link:**
https://www.kaggle.com/datasets/tongpython/cat-and-dog

The dataset contains two classes:

- Cat
- Dog

The images were resized to **128 × 128** pixels before training.

---

## Libraries Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Pillow (PIL)
- Scikit-learn

---

## Methodology

The project was completed in the following steps:

1. Loaded the Cats vs Dogs dataset.
2. Displayed sample images and analyzed the dataset.
3. Preprocessed the images by resizing and normalizing pixel values.
4. Split the dataset into 80% training and 20% validation.
5. Built a Convolutional Neural Network (CNN).
6. Trained the model for 10 epochs.
7. Evaluated the model using different performance metrics.
8. Visualized the training and validation accuracy and loss.

---

## CNN Architecture

The CNN model consists of the following layers:

- Conv2D (32 filters, ReLU)
- MaxPooling2D
- Conv2D (64 filters, ReLU)
- MaxPooling2D
- Conv2D (128 filters, ReLU)
- MaxPooling2D
- Flatten Layer
- Dense Layer (128 neurons, ReLU)
- Output Layer (1 neuron, Sigmoid)

Optimizer:
- Adam

Loss Function:
- Binary Crossentropy

Evaluation Metric:
- Accuracy

---

## Results

The model was successfully trained for **10 epochs**.

The model achieved good training accuracy and satisfactory validation accuracy for classifying cat and dog images.

The evaluation included:

- Test Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Accuracy Graph
- Loss Graph

---

## Conclusion

A Convolutional Neural Network (CNN) was successfully developed to classify images of cats and dogs. The model learned important image features through convolution and pooling layers, resulting in good classification performance. Compared to a traditional Artificial Neural Network (ANN), CNN automatically extracts image features and performs better on image-related tasks. Although CNNs require more computational resources and larger datasets for training, they are highly effective for image classification problems. This project demonstrates the practical application of deep learning in computer vision.

---

## Repository Structure

```
Assignment-9/
│
├── Assignment-9.ipynb
├── README.md
└── PetImages/
