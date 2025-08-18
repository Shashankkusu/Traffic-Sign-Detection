# 🚦 Traffic Sign Recognition with Deep Learning

## 📘 Project Overview
This project demonstrates the development of a Convolutional Neural Network (CNN) to classify traffic sign images using the German Traffic Sign Recognition Benchmark (GTSRB) dataset. The model achieves an impressive accuracy of 98.4%, showcasing the power of deep learning in autonomous vehicle applications.

---

## 🔧 Technologies Used

- **Deep Learning Framework:** Keras with TensorFlow backend
- **Programming Language:** Python

**Libraries:**
- NumPy
- Pandas
- Matplotlib
- OpenCV
- scikit-learn
- Keras

---

## 📊 Dataset

The model is trained on the German Traffic Sign Recognition Benchmark (GTSRB), which consists of over 50,000 labeled images across 43 traffic sign classes. The dataset is split into training and testing sets to evaluate model performance.

---

## 🧪 Steps Involved

### Data Preprocessing
- Loading and visualizing the dataset
- Resizing images to a uniform size
- Normalizing pixel values
- Splitting data into training and testing sets

### Model Architecture
- Building a CNN with multiple convolutional and pooling layers
- Flattening the output and adding dense layers
- Compiling the model with Adam optimizer and categorical crossentropy loss

### Model Training
- Training the model with the training data
- Evaluating performance on the test set

### Model Evaluation
- Generating classification reports
- Visualizing confusion matrices

---

## 📈 Model Performance

The trained model achieves an accuracy of **98.4%** on the test set, demonstrating its effectiveness in classifying traffic signs.

---

## 🖼️ Visualizations

The notebook includes various visualizations such as:
- Sample images from each class
- Training and validation accuracy/loss curves
- Confusion matrix heatmaps

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Shashankkusu/Traffic-Sign-Detection.git
   cd Traffic-Sign-Detection
   ```

2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter notebook:**
   ```bash
   jupyter notebook traffic sign detection.ipynb
   ```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
