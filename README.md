
# 🌾 Rice Image Classification
![Alt text](https://github.com/jeevitharamsudha16/Rice-Variety-Classification-using-CNN/blob/main/rice.jpg?raw=true)



This project classifies different varieties of rice grains using deep learning. The model is trained on a rice grain image dataset with the goal of building a robust classifier to identify rice types accurately.

## 📁 Dataset

We used the [Rice Leaf Disease Dataset](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset) *(or mention your dataset source)*. It includes labeled images of the following rice types:

- **Jasmine**
- **Karacadag**
- **Basmati**
- **Arborio**
- **Ipsala**

Each image is a close-up of individual rice grains.

## 🧠 Model Architecture

We used a Convolutional Neural Network (CNN) implemented using **TensorFlow**/**Keras**:

- Input Layer: Image resized to `128x128`
- 3 Convolutional + MaxPooling Layers
- Flatten
- Dense Layer (ReLU)
- Dropout (optional)
- Output Layer (Softmax)

Alternatively, for better performance, a pre-trained model like **MobileNetV2**, **ResNet50**, or **EfficientNetB0** can be used with transfer learning.

## 📊 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision, Recall, F1-Score (per class)

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/rice-image-classification.git
cd rice-image-classification
pip install -r requirements.txt
