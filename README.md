# Detect-Pneumonia-from-Chest-X-Ray-Images

Chest X-rays are necessary for detecting pneumonia because they provide critical visual information about the condition of the lungs. This allows healthcare providers to diagnose the disease, assess its severity, and differentiate it from other respiratory conditions. The ability to quickly and accurately identify pneumonia on an X-ray is crucial for initiating appropriate treatment and improving patient outcomes.

The code provided is designed to detect pneumonia from chest X-ray images using a Convolutional Neural Network (CNN) implemented in TensorFlow Keras. 

### Process:
The process begins by loading and preprocessing the dataset, which includes dynamic augmentation techniques to enhance the model's robustness. The model architecture includes multiple convolutional layers with batch normalization, dropout, and residual connections to improve feature extraction and prevent overfitting. The network is trained on augmented data, and after training, it predicts whether an X-ray shows signs of pneumonia. The results, including the true and predicted labels, are then visualized on a 3x3 grid of sample images, enabling a clear assessment of the model's performance in identifying pneumonia.

### Dataset used:
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia


