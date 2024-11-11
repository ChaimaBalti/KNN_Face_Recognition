# KNN Face Recognition

## Overview
The **KNN Face Recognition** project implements a K-Nearest Neighbors (KNN) algorithm for face recognition tasks. This project leverages image data to classify faces based on their features extracted from photographs. The KNN algorithm is known for its simplicity and effectiveness in handling classification problems, making it suitable for this face recognition application.

### Acknowledgments
This project contains code from [ageitgey/face_recognition](https://github.com/ageitgey/face_recognition), with minor modifications to fit the needs of this project. Many thanks to [@ageitgey](https://github.com/ageitgey) for the original code and for making it available under an open-source license.

## Features
- **KNN Algorithm**: Implements the KNN algorithm for face classification.
- **Data Preprocessing**: Includes methods for preprocessing images, such as resizing and normalization.
- **Model Evaluation**: Evaluate model performance using accuracy metrics and confusion matrices.
- **Visualization**: Visualizes the results of face recognition through plots and sample predictions.

## Getting Started
To get a local copy of this project up and running, follow these steps:

### Prerequisites
Ensure you have Python installed on your system. This project is developed and tested with Python 3.x.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ChaimaBalti/KNN_Face_Recognition.git
   cd KNN_Face_Recognition
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
- To train the KNN model and perform face recognition, run the main script:
   ```bash
   python knn_face_recognition.py
   ```

## Model Evaluation
The model's performance can be assessed using various metrics such as accuracy and F1 score. Detailed evaluation results will be output during the model execution.

## Contributing
Contributions are welcome! If you have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [scikit-learn](https://scikit-learn.org/stable/) - for the KNN implementation.
- [OpenCV](https://opencv.org/) - for image processing utilities.
- [Matplotlib](https://matplotlib.org/) - for visualizations.

```
