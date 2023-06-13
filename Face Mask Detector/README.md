# Face Mask Detection

This repository contains the code and resources for implementing a face mask detection system using computer vision techniques. The system aims to detect whether a person is wearing a face mask or not in real-time using a webcam or pre-recorded video.

## Overview

The face mask detection system is built using Python and OpenCV library. It utilizes a pre-trained deep learning model to classify faces into two categories: with mask and without mask. The system performs real-time face detection, followed by mask classification for each detected face.

## Installation

To run the face mask detection system, follow these steps:

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/sivaragul1/face-mask-detection.git
   ```

2. Install the required dependencies. It is recommended to set up a virtual environment before installing the dependencies to keep your Python environment isolated:
   ```
   pip install -r requirements.txt
   ```

3. Download the pre-trained face mask detection model weights and place them in the `model` directory.

4. Run the main script to start the face mask detection system:
   ```
   python main.py
   ```

## Usage

Once the face mask detection system is running, it will utilize your webcam or the specified video file for face detection and mask classification. Detected faces will be annotated with bounding boxes and labels indicating whether a mask is present or not.

You can adjust the system's settings, such as video source, confidence threshold, and display options, by modifying the configuration variables in the `config.py` file.

## Contributing

Contributions to this face mask detection project are welcome. If you have any improvements, bug fixes, or new features to propose, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the code for personal and commercial purposes.

## Acknowledgements

- The face mask detection model used in this project is based on the [MobileNetV2](https://arxiv.org/abs/1801.04381) architecture and was trained on a custom dataset.
- Special thanks to the creators and contributors of the open-source libraries and resources used in this project.

If you have any questions or feedback, please don't hesitate to contact me.

### Enjoy detecting face masks!
