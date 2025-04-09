# FaceAgeMood 🎭📅

FaceAgeMood is a dual deep learning project that uses facial images to perform **age prediction** and **emotion detection**. This project demonstrates how a single dataset can be used for multiple facial analysis tasks.

## 📁 Dataset

This project uses the [UTKFace (new) dataset](https://www.kaggle.com/datasets/jangedoo/utkface-new) from Kaggle.

The dataset contains over 20,000 facial images labeled with:

- **Age**
- **Gender**
- **Ethnicity**

Although the dataset doesn't include emotion labels by default, I leveraged facial expressions from the images for an experimental **emotion detection** task.

## 🧠 Notebooks

| Notebook | Description |
|---------|-------------|
| `Age_prediction.ipynb` | Predicts age from facial images using a convolutional neural network (CNN). |
| `emotion-detection.ipynb` | Detects emotion from the same UTKFace images using a custom approach. |

## 🛠️ Features

- Image preprocessing using OpenCV and TensorFlow/Keras
- CNN architectures for both age and emotion tasks
- Custom data labeling and augmentation for emotion prediction
- Evaluation metrics and visualizations for performance insight

Main libraries used:

    TensorFlow / Keras

    OpenCV

    Matplotlib

    NumPy

    scikit-learn


📜 License

This project is open-sourced under the MIT License.
🙋‍♂️ Author

Made with ❤️ by Tareq
