# CNN Image Classification Model

This project is a Convolutional Neural Network (CNN) implemented using TensorFlow and Keras for image classification. The model trains on a dataset of images, applies data augmentation, and evaluates its performance on a test dataset. A confusion matrix and classification report are generated to assess model accuracy.

## Features
- Data augmentation for improved generalization.
- CNN architecture with three convolutional layers and max-pooling.
- Supports multi-class classification.
- Evaluation using confusion matrix and classification report.
- Visualization of random predictions.
- Model saving in TensorFlow `.keras` format.

## Dataset
The project assumes the dataset is structured as follows:

./CNN_dataset/
    ├── train/
    │   ├── class_1/
    │   ├── class_2/
    │   └── ...
    └── test/
        ├── class_1/
        ├── class_2/
        └── ...

## Requirements
- Python 3.7+
- TensorFlow 2.0+
- NumPy
- Matplotlib
- Seaborn
- TQDM
- scikit-learn


## Model Evaluation
- **Confusion Matrix**: Visualized using Seaborn's heatmap.
- **Classification Report**: Displays precision, recall, and F1-score for each class.
- **Random Predictions**: Visualizes a few predictions with their true and predicted labels.

## Results
The model achieves test accuracy of approximately **0.9933%** (based on your dataset). Check the output for detailed metrics.

## Contributors
- [Shafat Hossain](https://github.com/shafat21)
- [Marjana Akter](https://github.com/marjana15)

## License
This project is licensed under the MIT License.
