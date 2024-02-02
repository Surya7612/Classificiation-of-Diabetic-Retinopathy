# RetinaSpec: Diabetic Retinopathy Classification
## Overview
RetinaSpec is a cutting-edge tool designed for the precise classification of Diabetic Retinopathy severity levels through deep learning techniques. Developed from January 2021 to July 2021, this project leverages the power of transfer learning and an ensemble of state-of-the-art models to analyze retina images, providing a significant tool in the fight against this vision-threatening disease.

## Features
**Advanced Classification Accuracy**: Utilizes an ensemble approach combining VGG16, ResNet50, DenseNet201, InceptionV3, InceptionResNetV2, and Xception models for high accuracy.
**Transfer Learning**: Employs models pre-trained on the ImageNet dataset to ensure robust feature extraction.
**User-Friendly Interface**: Designed for ease of use by medical professionals and researchers.

## Getting Started
### Prerequisites
* Python 3.8+
* TensorFlow 2.x
* Keras
* NumPy
* OpenCV

### Installation
Clone the repository to your local machine:
```bash
git clone https://github.com/Surya7612/Classificiation-of-Diabetic-Retinopathy.git
```
Install the required dependencies:
```bash
pip install -r requirements.txt
```
### Usage
To run the classification tool:
1. Run `diab_class_EDA.ipynb`
2. Run `ensemble_all_models.ipynb`

### How It Works
RetinaSpec integrates multiple deep learning models pre-trained on ImageNet, leveraging their strengths through an ensemble method. This approach allows for nuanced differentiation between severity levels of Diabetic Retinopathy, significantly improving classification performance.

### Contributing
We welcome contributions from the community. If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

### Team
* Surya Nediyadeth - Lead Developer - Led the development team and designed the core architecture.
* Freddy Biju - Data Scientist - Specialized in model training and optimization.
* Rohit R. - Data Scientist - Specialized in model training and optimization.

### Acknowledgments
Thanks to the creators of the pre-trained models used in this project.
Appreciation to our team members, and our mentor for their dedication and hard work.

## References
* VGG16
* ResNet50
* DenseNet201
* InceptionV3
* InceptionResNetV2
* Xception
