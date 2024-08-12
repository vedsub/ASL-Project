# ASL to Text Converter

This project converts American Sign Language (ASL) into text using two different techniques. It aims to bridge communication gaps by providing an efficient way to translate sign language into written text.

## Table of Contents
- [Features](#features)
- [Techniques](#techniques)
- [Installation](#installation)
- [Dataset](#dataset)
- [Contributing](#contributing)


## Features
- Converts ASL gestures into text in real-time
- Utilizes two distinct techniques for conversion
- Trained on a combination of existing and custom datasets
- Deployed using TensorFlow Lite for efficient mobile and edge device usage

## Techniques

### 1. LSTM with OpenCV
This technique uses Long Short-Term Memory (LSTM) neural networks in combination with OpenCV for image processing. The model is deployed using TensorFlow Lite for efficient performance on mobile and edge devices.

### 2. Analyzed Data with Preset Distances
This method analyzes the distances between key points on the hand to recognize ASL gestures. It uses a preset database of distance relationships for various signs to perform the conversion.

## Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/asl-to-text-converter.git
cd asl-to-text-converter

# Install dependencies
pip install -r requirements.txt


## Dataset
The model was trained on a combination of:
1. Existing ASL datasets
2. Custom dataset created for fine-tuning

The custom dataset was created to improve accuracy and cover a wider range of ASL gestures without overfitting.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

