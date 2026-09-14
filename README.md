# Fashion Image Classification with Deep Learning

A Deep Learning project that automatically classifies fashion product images into predefined categories using **TensorFlow/Keras** and the **Fashion-MNIST** dataset.

The project demonstrates how an e-commerce company can use AI to reduce manual product categorization and improve the speed and consistency of product listing.

## 🚀 Project Overview

E-commerce companies receive large numbers of product images that need to be categorized before products can be added to an online store.

This project builds a neural network that takes a fashion product image as input and predicts its product category.

### Business Workflow

```text
Product Image
      ↓
Deep Learning Model
      ↓
Predicted Product Category
      ↓
Human Review (if required)
      ↓
Product Added to Website
```

## 🎯 Objectives

* Understand image classification using Deep Learning
* Build an Artificial Neural Network
* Train a model using labeled product images
* Evaluate model performance on unseen images
* Predict fashion product categories
* Understand the business application of AI in e-commerce

## 📊 Dataset

The project uses the **Fashion-MNIST** dataset.

| Dataset  | Images | Image Size |
| -------- | -----: | ---------: |
| Training | 60,000 |    28 × 28 |
| Testing  | 10,000 |    28 × 28 |

The model classifies images into 10 categories:

1. T-shirt/Top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle Boot

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab
* Fashion-MNIST

## 🧠 Model

The project uses an Artificial Neural Network to learn patterns from fashion product images.

The model is compiled using:

* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Crossentropy
* **Metric:** Accuracy

The notebook trains the model for **3 epochs** with a **10% validation split**.

## 📈 Results

The recorded training results improved across the three epochs:

| Epoch | Training Accuracy | Validation Accuracy |
| ----- | ----------------: | ------------------: |
| 1     |            81.52% |              84.93% |
| 2     |            85.62% |              86.27% |
| 3     |            86.83% |              86.93% |

### Test Performance

**Test Accuracy: 85.89%**

The model was also demonstrated making a prediction where the predicted category and actual category were both **Ankle Boot**.

> Results can vary slightly when the notebook is executed again.

## 💼 Business Application

This project can support an e-commerce product-listing workflow.

### Traditional Process

```text
Employee receives product image
          ↓
Employee manually selects category
          ↓
Product is added to website
```

### AI-Assisted Process

```text
Product image uploaded
          ↓
AI analyzes image
          ↓
AI predicts category
          ↓
Employee reviews result if required
          ↓
Product added to website
```

### Potential Business Benefits

* Faster product listing
* Reduced repetitive manual work
* More consistent product categorization
* Improved product-search experience
* Ability to process larger numbers of images

## 📁 Project Structure

```text
fashion-image-classification-deep-learning/
│
├── Deep_Learning_Fashion_Classification_Name.ipynb
├── README.md
│
└── screenshots/
    └── prediction-result.png
```

## ▶️ How to Run

### Option 1 — Google Colab

1. Open the `.ipynb` notebook in Google Colab.
2. Run the cells sequentially.
3. The Fashion-MNIST dataset downloads automatically.
4. Train the neural network.
5. Evaluate the model.
6. Try different test images by changing `image_number`.

Example:

```python
image_number = 25
```

## 🔍 Example Prediction

The notebook displays:

```text
Predicted Product: Ankle Boot
Actual Product: Ankle Boot
```

You can test other images by changing the image number.

## ⚠️ Limitations

The model is not guaranteed to classify every image correctly.

Before deploying a similar system in a real business environment, companies should consider:

* Cost of incorrect classifications
* Customer experience
* Training-data quality
* Model performance across categories
* Human review for uncertain predictions

Accuracy alone may not be sufficient for production deployment.

## 📚 Learning Outcomes

This project demonstrates that:

* Images can be used as input for Deep Learning models.
* Neural networks can learn patterns from historical examples.
* Training and testing are different stages of machine learning.
* A trained model can predict categories for unseen images.
* AI predictions are not always correct.
* Human oversight can remain important in business AI systems.

## 👨‍💻 Project Type

**Academic / BBA AI & ML Practical Project**

**Domain:** Artificial Intelligence, Machine Learning, E-commerce

## 📌 Future Improvements

Possible improvements include:

* Use a Convolutional Neural Network (CNN)
* Increase the number of training epochs
* Add data augmentation
* Compare different architectures
* Analyze class-wise performance
* Add a confusion matrix
* Build a simple web interface for image uploads
* Deploy the model as an e-commerce classification service

## 📄 License

This project is intended for educational and academic purposes.
