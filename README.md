# Handwriting Recognition with Convolutional Neural Network

This repository contains two scripts that demonstrate handwriting recognition using a Convolutional Neural Network (CNN) in TensorFlow. The scripts use the MNIST handwriting dataset for training and provide a simple GUI interface for drawing digits and classifying them.

## Requirements

- Python 3.x
- TensorFlow
- Pygame

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/David-Ademola/Handwriting-Recognition.git
   cd handwriting-recognition
   ```

2. Install the required dependencies:

   ```
   pip install tensorflow pygame
   ```

## Usage

### Training the Model

To train the CNN model, run the following command:

```
python train_model.py model.h5
```

This script loads the MNIST dataset, normalizes the input images, prepares the data for training, creates the CNN model, and trains the model for 10 epochs. After training, the model's performance is evaluated on the test set.

### Handwriting Recognition GUI

To use the handwriting recognition GUI, run the following command:

```
python recognition.py model.h5
```

Replace `model.h5` with the path to a trained model file (e.g., `model.h5`). The GUI window will appear, allowing you to draw digits using the mouse. Click the "Classify" button to classify the drawn digit. The predicted digit will be displayed on the screen. You can click the "Reset" button to clear the drawing.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to create an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- The MNIST dataset is used for training the model.
