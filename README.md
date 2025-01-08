
# Facial Expression Recognition (FER)


This project implements a **Facial Expression Recognition (FER)** system using Convolutional Neural Networks (CNNs) with TensorFlow and Keras. The goal is to classify facial expressions into seven categories, enabling automated analysis of human emotions from images.

## Features

- **Preprocessing**: Includes image resizing, normalization, and data augmentation.
- **Model Architecture**: Employs a CNN with layers such as Conv2D, MaxPooling2D, Dropout, and Dense for robust feature extraction.
- **Training and Validation**: Trains the model on a labeled dataset with real-time validation.
- **Evaluation**: Analyzes model performance with metrics like accuracy and loss.

## Requirements

- Python 3.8 or higher
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib

Install dependencies using:
```bash
pip install tensorflow numpy matplotlib
```

## Dataset

The project uses a dataset with images of facial expressions categorized into the following classes:
1. **Angry**
2. **Disgust**
3. **Fear**
4. **Happy**
5. **Neutral**
6. **Sad**
7. **Surprise**

### Dataset Directory Structure
```
dataset/
├── train/
│   ├── angry/
│   ├── disgust/
│   ├── fear/
│   ├── happy/
│   ├── neutral/
│   ├── sad/
│   └── surprise/
├── validation/
│   ├── angry/
│   ├── disgust/
│   ├── fear/
│   ├── happy/
│   ├── neutral/
│   ├── sad/
│   └── surprise/
```

### Preprocessing Steps
- Images resized to 48x48 pixels.
- Normalized pixel values between 0 and 1.
- Augmented data to improve model generalization.

## Model Architecture

- **Convolutional Layers**: Extract spatial features from images.
- **MaxPooling Layers**: Reduce dimensionality and retain key features.
- **Dropout**: Prevent overfitting.
- **Dense Layer**: Output layer with 7 nodes for classification.

## Training

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Batch Size: 64
- Epochs: 50



## Results

- Visualizes training and validation accuracy/loss curves.
- Predicts facial expressions for unseen images.

## Future Improvements

- Use advanced architectures like ResNet or MobileNet for enhanced accuracy.
- Incorporate real-time facial expression detection using a webcam.

## Contribution

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

---

