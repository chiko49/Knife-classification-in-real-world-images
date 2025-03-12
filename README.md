# Knife-classification-in-real-world-images
# Project Overview

This project, **Knife Classification in Real-World Images**, aims to accurately classify knives from diverse and dynamic visual landscapes using advanced Convolutional Neural Network (CNN) architectures. The project leverages ResNet18 and VGG16 to extract features from knife images, enhancing public safety through improved detection accuracy in real-world scenarios.

## Objectives

- Classify knives in real-world images using advanced deep learning models.
- Compare the performance of ResNet18 and VGG16 for knife detection.
- Analyze the impact of hyperparameters on model accuracy and efficiency.
- Ensure the model is robust against diverse lighting conditions and backgrounds.

## Key Features

- **CNN-Based Knife Detection**: Utilizes ResNet18 and VGG16 to classify knife images.
- **Hyperparameter Optimization**: Fine-tunes learning rates, batch sizes, and training epochs for maximum accuracy.
- **Data Augmentation**: Enhances the dataset with transformations like cropping, flipping, and rotating.
- **Performance Metrics**: Evaluates accuracy, mean Average Precision (mAP), and loss for comprehensive model assessment.

## Technology Stack

- **Programming Language**: Python
- **Frameworks/Libraries**: PyTorch, OpenCV, NumPy
- **Version Control**: Git and GitHub

## Configuration Details

### ResNet18 Configuration:
- Number of Classes: 192
- Image Dimensions: 224x224
- Batch Size: 16
- Epochs: 30
- Learning Rate: 0.00007

### VGG16 Configuration:
- Number of Classes: 192
- Image Dimensions: 224x224
- Batch Size: 16
- Epochs: 40
- Learning Rate: 0.00001

## Installation Instructions

Ensure the following prerequisites are installed on your system:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/repo-name.git
   ```

2. Navigate to the project directory:

   ```bash
   cd repo-name
   ```

3. Set up the environment:

   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

## Usage Guidelines

To execute the project, follow these steps:

```bash
# Run the main script for ResNet18
python main_resnet.py

# Run the main script for VGG16
python main_vgg16.py
```

Ensure you have the knife dataset and necessary environment configurations in place.

### Model Performance:

- **ResNet18 Accuracy (mAP)**: 66.4%
- **VGG16 Accuracy (mAP)**: 65.8%

## Contribution Guidelines

We welcome contributions to enhance the project. Please follow the process below:

1. Fork the repository and create a new branch:

   ```bash
   git checkout -b feature/new-feature
   ```

2. Commit your changes with a meaningful message:

   ```bash
   git commit -m "Add knife detection improvement"
   ```

3. Push your changes and open a Pull Request:

   ```bash
   git push origin feature/new-feature
   ```

## License

This project is licensed under the [License Name] License. See the `LICENSE` file for details.

## Contact

For any queries or support, reach out via [kaustubh.wankhede1999@gmail.com](mailto:kaustubh.wankhede1999@gmail.com) or raise an issue on the repository.

